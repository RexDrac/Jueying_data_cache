expert-num: 6
state-dim: 25
critic-lr: 0.0003
loss-output-bound-coeff: 0.0
max-path-num: 20
max-step-num: 2500000000
interpolation: False
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
actor-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
critic-l2-reg: 0.0003
actor-l2-reg: 0.0003
replay-buffer-size: 1000000
max-path-step: 5000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
max-train-time: 10
loss-entropy-coeff: 0.0
batch-size: 128
max-test-time: 10
joint-interpolation: True
tau: 0.001
task-weight: 0.2
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
action-dim: 12
critic-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-layer-size: [256, 256]
rollout-step-num: 1
replay-start-size: 10000
filter-action: True
imitation-weight: 0.4
max-episode-num: 5000000
loss-output-smooth-coeff: 2.0
prioritized-exp-replay: True
filter-torque: False
dsr-gait-freq: 1.667
gating-layer-size: [128, 128]
dsr-gait-period: 0.6
squash-action: True
HLC-frequency: 25
loss-output-diff-coeff: 0
critic-layer-size: [256, 256]
total-step-num: 2500000000
env-id: HumanoidBalanceFilter-v0
replay-ratio: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
Physics-frequency: 1000
actor-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
reward-scale: 0.1
test-num: 4
record-start-size: 10000.0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
LLC-frequency: 500
bullet-default-PD: False
gamma: 0.986
epoch-num: 500
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
render-eval: False
goal-weight: 0.4
critic-weight-decay: 1e-06
