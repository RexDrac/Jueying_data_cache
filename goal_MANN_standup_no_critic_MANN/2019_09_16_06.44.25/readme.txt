normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
rollout-step-num: 1
replay-ratio: 1
gamma: 0.955
record-start-size: 10000.0
imitation-weight: 0.5
squash-action: True
total-step-num: 2500000000
render-eval: False
HLC-frequency: 25
actor-l2-reg: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
tau: 0.001
loss-output-smooth-coeff: 2.0
actor-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
n-step: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
filter-torque: False
expert-num: 8
actor-lr: 0.0003
LLC-frequency: 500
epoch-num: 500
joint-interpolation: True
loss-output-diff-coeff: 0
filter-action: True
critic-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
critic-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
dsr-gait-period: 0.6
epoch-step-num: 5000000
replay-start-size: 10000
task-weight: 0.5
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
gating-layer-size: [128, 128]
critic-weight-decay: 1e-06
max-path-num: 20
max-train-time: 10
max-step-num: 2500000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
interpolation: False
max-path-step: 5000
state-dim: 25
replay-buffer-size: 1000000
bullet-default-PD: False
loss-entropy-coeff: 0.0
actor-layer-size: [256, 256]
train-step-num: 1
max-episode-num: 5000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
test-num: 4
prioritized-exp-replay: True
critic-activation-fn: ['relu', 'relu', 'None']
dsr-gait-freq: 1.667
max-test-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
actor-weight-decay: 1e-06
env-id: HumanoidBalanceFilter-v0
Physics-frequency: 1000
critic-layer-size: [256, 256]
