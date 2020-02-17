critic-weight-decay: 1e-06
max-path-step: 5000
rollout-step-num: 1
max-episode-num: 5000000
replay-ratio: 1
actor-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
interpolation: False
goal-weight: 0.4
reward-scale: 0.1
actor-lr: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
epoch-num: 500
HLC-frequency: 25
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-step-num: 2500000000
state-dim: 25
critic-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-weight-decay: 1e-06
loss-output-bound-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-action: True
task-weight: 0.2
expert-num: 6
tau: 0.001
critic-lr: 0.0003
action-dim: 12
loss-output-diff-coeff: 0
critic-l2-reg: 0.0003
test-num: 4
dsr-gait-period: 0.6
loss-output-smooth-coeff: 2.0
filter-torque: False
loss-entropy-coeff: 0.0
replay-start-size: 10000
render-eval: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
gamma: 0.986
bullet-default-PD: False
LLC-frequency: 500
joint-interpolation: True
batch-size: 128
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
max-test-time: 10
actor-layer-size: [256, 256]
gating-layer-size: [128, 128]
epoch-step-num: 5000000
n-step: 1
prioritized-exp-replay: True
critic-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
squash-action: True
replay-buffer-size: 1000000
record-start-size: 10000.0
total-step-num: 2500000000
dsr-gait-freq: 1.667
imitation-weight: 0.4
