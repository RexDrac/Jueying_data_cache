dsr-gait-period: 0.6
actor-lr: 0.0003
bullet-default-PD: False
imitation-weight: 0.5
state-dim: 25
replay-ratio: 1
Physics-frequency: 1000
batch-size: 128
max-train-time: 10
filter-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-layer-size: [128, 128]
loss-entropy-coeff: 0.0
action-dim: 12
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-l2-reg: 0.0003
task-weight: 0.5
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
epoch-step-num: 5000000
max-test-time: 10
loss-output-smooth-coeff: 2.0
record-start-size: 10000.0
joint-interpolation: True
max-path-step: 5000
critic-weight-decay: 1e-06
actor-weight-decay: 1e-06
actor-layer-size: [256, 256]
env-id: HumanoidBalanceFilter-v0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
total-step-num: 2500000000
LLC-frequency: 500
max-path-num: 20
replay-buffer-size: 1000000
loss-output-bound-coeff: 0.0
filter-torque: False
render-eval: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-step-num: 2500000000
HLC-frequency: 25
expert-num: 8
max-episode-num: 5000000
dsr-gait-freq: 1.667
train-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
squash-action: True
rollout-step-num: 1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
epoch-num: 500
critic-l2-reg: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
critic-layer-size: [256, 256]
test-num: 4
critic-activation-fn: ['relu', 'relu', 'None']
gamma: 0.955
interpolation: False
replay-start-size: 10000
loss-output-diff-coeff: 0
n-step: 1
critic-lr: 0.0003
tau: 0.001
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
