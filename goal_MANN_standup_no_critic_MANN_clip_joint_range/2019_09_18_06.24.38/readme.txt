interpolation: False
loss-output-diff-coeff: 0
n-step: 1
test-num: 4
total-step-num: 2500000000
bullet-default-PD: False
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
rollout-step-num: 1
critic-lr: 0.0003
reward-scale: 0.1
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
dsr-gait-period: 0.6
task-weight: 0.5
replay-start-size: 10000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-step: 5000
actor-weight-decay: 1e-06
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
expert-num: 8
record-start-size: 10000.0
replay-ratio: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
gating-layer-size: [128, 128]
max-path-num: 20
LLC-frequency: 500
actor-layer-size: [256, 256]
batch-size: 128
action-dim: 12
loss-output-smooth-coeff: 1.0
replay-buffer-size: 1000000
gamma: 0.986
loss-entropy-coeff: 0.0
Physics-frequency: 1000
actor-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
max-test-time: 10
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
critic-activation-fn: ['relu', 'relu', 'None']
filter-action: True
epoch-num: 500
max-train-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
squash-action: True
dsr-gait-freq: 1.667
epoch-step-num: 5000000
filter-torque: False
critic-layer-size: [256, 256]
joint-interpolation: True
gating-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
imitation-weight: 0.5
max-step-num: 2500000000
prioritized-exp-replay: True
actor-activation-fn: ['relu', 'relu', 'None']
render-eval: False
loss-output-bound-coeff: 0.0
actor-lr: 0.0003
state-dim: 25
critic-weight-decay: 1e-06
train-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
HLC-frequency: 25
critic-l2-reg: 0.0003
