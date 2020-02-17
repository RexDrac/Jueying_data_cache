controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
tau: 0.001
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gamma: 0.955
prioritized-exp-replay: True
test-num: 4
train-step-num: 1
loss-output-diff-coeff: 0
loss-output-smooth-coeff: 1.0
render-eval: False
loss-output-bound-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
dsr-gait-period: 0.6
env-id: HumanoidBalanceFilter-v0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
joint-interpolation: True
imitation-weight: 0.5
state-dim: 25
n-step: 1
critic-lr: 0.0003
max-test-time: 10
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
HLC-frequency: 25
filter-action: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
total-step-num: 2500000000
filter-torque: False
squash-action: True
max-step-num: 2500000000
actor-weight-decay: 1e-06
actor-l2-reg: 0.0003
record-start-size: 10000.0
gating-layer-size: [128, 128]
actor-layer-size: [256, 256]
max-path-step: 5000
LLC-frequency: 500
rollout-step-num: 1
bullet-default-PD: False
replay-buffer-size: 1000000
Physics-frequency: 1000
epoch-step-num: 5000000
critic-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
task-weight: 0.5
epoch-num: 500
batch-size: 128
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
dsr-gait-freq: 1.667
interpolation: False
reward-scale: 0.1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
loss-entropy-coeff: 0.0
replay-start-size: 10000
max-episode-num: 5000000
expert-num: 4
action-dim: 12
critic-layer-size: [256, 256]
critic-weight-decay: 1e-06
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
