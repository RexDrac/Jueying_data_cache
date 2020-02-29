gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
max-episode-num: 5000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
render-eval: False
actor-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-train-time: 10
interpolation: False
max-path-num: 20
batch-size: 128
HLC-frequency: 25
prioritized-exp-replay: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
total-step-num: 2500000000
loss-entropy-coeff: 0.0
record-start-size: 10000.0
reward-scale: 0.1
squash-action: True
critic-weight-decay: 1e-06
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-step-num: 5000000
actor-l2-reg: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
gating-layer-size: [128, 128]
filter-torque: False
rollout-step-num: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-bound-coeff: 0.0
max-path-step: 5000
env-id: HumanoidBalanceFilter-v0
state-dim: 25
train-step-num: 1
filter-action: True
max-test-time: 10
replay-buffer-size: 1000000
Physics-frequency: 1000
imitation-weight: 0.4
actor-lr: 0.0003
n-step: 1
joint-interpolation: True
task-weight: 0.2
actor-weight-decay: 1e-06
critic-layer-size: [256, 256]
tau: 0.001
max-step-num: 2500000000
loss-output-smooth-coeff: 2.0
goal-weight: 0.4
dsr-gait-freq: 1.667
gamma: 0.986
loss-output-diff-coeff: 0
LLC-frequency: 500
expert-num: 6
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
bullet-default-PD: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
replay-start-size: 10000
epoch-num: 500
replay-ratio: 1
critic-lr: 0.0003
test-num: 4
action-dim: 12
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
