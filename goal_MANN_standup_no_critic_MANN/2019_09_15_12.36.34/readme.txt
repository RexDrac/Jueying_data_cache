actor-layer-size: [256, 256]
n-step: 1
epoch-num: 500
record-start-size: 10000.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-entropy-coeff: 0.0
test-num: 4
max-train-time: 10
max-path-step: 5000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-freq: 1.667
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
critic-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
gamma: 0.986
max-step-num: 2500000000
max-test-time: 10
task-weight: 0.5
epoch-step-num: 5000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
replay-start-size: 10000
rollout-step-num: 1
loss-output-smooth-coeff: 2.0
actor-lr: 0.0003
LLC-frequency: 500
prioritized-exp-replay: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-layer-size: [128, 128]
critic-layer-size: [256, 256]
actor-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
interpolation: False
action-dim: 12
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-bound-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
joint-interpolation: True
env-id: HumanoidBalanceFilter-v0
tau: 0.001
state-dim: 25
squash-action: True
total-step-num: 2500000000
Physics-frequency: 1000
critic-weight-decay: 1e-06
max-path-num: 20
render-eval: False
batch-size: 128
critic-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-ratio: 1
imitation-weight: 0.5
bullet-default-PD: False
replay-buffer-size: 1000000
dsr-gait-period: 0.6
gating-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
max-episode-num: 5000000
expert-num: 8
filter-torque: False
train-step-num: 1
filter-action: True
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-l2-reg: 0.0003
loss-output-diff-coeff: 0
