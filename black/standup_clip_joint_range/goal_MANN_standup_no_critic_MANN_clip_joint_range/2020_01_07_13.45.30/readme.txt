actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
rollout-step-num: 1
loss-entropy-coeff: 0.0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-output-bound-coeff: 0.0
filter-torque: False
bullet-default-PD: False
prioritized-exp-replay: True
imitation-weight: 0.4
HLC-frequency: 100
critic-l2-reg: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
expert-num: 8
critic-activation-fn: ['relu', 'relu', 'None']
dsr-gait-freq: 1.667
squash-action: True
LLC-frequency: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-lr: 0.0003
test-num: 4
batch-size: 128
render-eval: False
reward-scale: 0.1
interpolation: False
max-episode-num: 5000000
epoch-num: 500
max-path-num: 20
actor-activation-fn: ['relu', 'relu', 'None']
gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-start-size: 10000
max-train-time: 10
critic-lr: 0.0003
joint-interpolation: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
total-step-num: 2500000000
state-dim: 25
filter-action: True
record-start-size: 10000.0
env-id: HumanoidBalanceFilter-v0
Physics-frequency: 1000
tau: 0.001
gamma: 0.997
gating-layer-size: [128, 128]
task-weight: 0.2
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-layer-size: [256, 256]
actor-layer-size: [256, 256]
epoch-step-num: 5000000
actor-l2-reg: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-ratio: 1
action-dim: 12
loss-output-diff-coeff: 0
max-test-time: 10
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
dsr-gait-period: 0.6
n-step: 1
max-path-step: 5000
loss-output-smooth-coeff: 8.0
replay-buffer-size: 1000000
critic-weight-decay: 1e-06
max-step-num: 2500000000
goal-weight: 0.4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-weight-decay: 1e-06
