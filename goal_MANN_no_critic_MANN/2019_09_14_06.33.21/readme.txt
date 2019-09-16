action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-weight-decay: 1e-06
loss-entropy-coeff: 0.0
dsr-gait-period: 0.6
critic-l2-reg: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
joint-interpolation: True
gamma: 0.955
max-step-num: 2500000000
tau: 0.001
render-eval: False
actor-weight-decay: 1e-06
loss-output-smooth-coeff: 1.0
action-dim: 12
Physics-frequency: 1000
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
filter-action: True
squash-action: True
max-train-time: 10
env-id: HumanoidBalanceFilter-v0
expert-num: 4
actor-l2-reg: 0.0003
batch-size: 128
critic-layer-size: [256, 256]
interpolation: False
loss-output-diff-coeff: 0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
record-start-size: 10000.0
replay-buffer-size: 1000000
reward-scale: 0.1
epoch-num: 500
max-episode-num: 5000000
gating-layer-size: [128, 128]
max-path-num: 20
critic-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
epoch-step-num: 5000000
dsr-gait-freq: 1.667
gating-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-ratio: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
total-step-num: 2500000000
test-num: 4
prioritized-exp-replay: True
max-test-time: 10
task-weight: 0.5
actor-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 25
train-step-num: 1
LLC-frequency: 500
max-path-step: 5000
loss-output-bound-coeff: 0.0
rollout-step-num: 1
filter-torque: False
imitation-weight: 0.5
n-step: 1
