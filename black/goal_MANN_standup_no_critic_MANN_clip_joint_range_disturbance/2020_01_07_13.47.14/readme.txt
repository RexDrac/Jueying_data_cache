rollout-step-num: 1
goal-weight: 0.4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
interpolation: False
expert-num: 8
replay-buffer-size: 1000000
test-num: 4
task-weight: 0.2
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
replay-ratio: 1
critic-layer-size: [256, 256]
actor-lr: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-action: True
joint-interpolation: True
loss-output-diff-coeff: 0
gating-layer-size: [128, 128]
max-step-num: 2500000000
squash-action: True
env-id: HumanoidBalanceFilter-v0
epoch-step-num: 5000000
critic-lr: 0.0003
total-step-num: 2500000000
gating-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-layer-size: [256, 256]
critic-weight-decay: 1e-06
actor-l2-reg: 0.0003
LLC-frequency: 500
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
loss-output-bound-coeff: 0.0
critic-l2-reg: 0.0003
dsr-gait-period: 0.6
Physics-frequency: 1000
actor-weight-decay: 1e-06
filter-torque: False
dsr-gait-freq: 1.667
train-step-num: 1
max-episode-num: 5000000
loss-entropy-coeff: 0.0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
loss-output-smooth-coeff: 8.0
gamma: 0.997
bullet-default-PD: False
max-path-step: 5000
reward-scale: 0.1
record-start-size: 10000.0
replay-start-size: 10000
max-train-time: 10
max-test-time: 10
imitation-weight: 0.4
HLC-frequency: 100
epoch-num: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
render-eval: False
max-path-num: 20
state-dim: 25
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
n-step: 1
tau: 0.001
