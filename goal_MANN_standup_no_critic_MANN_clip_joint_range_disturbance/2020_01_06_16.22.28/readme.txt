HLC-frequency: 100
record-start-size: 10000.0
loss-entropy-coeff: 0.0
tau: 0.001
joint-interpolation: True
expert-num: 8
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
max-test-time: 10
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
dsr-gait-freq: 1.667
gating-layer-size: [128, 128]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
filter-action: True
bullet-default-PD: False
epoch-step-num: 5000000
squash-action: True
critic-weight-decay: 1e-06
max-step-num: 2500000000
gamma: 0.997
batch-size: 128
render-eval: False
imitation-weight: 0.4
replay-ratio: 1
replay-buffer-size: 1000000
test-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
n-step: 1
Physics-frequency: 1000
critic-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 2.0
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
total-step-num: 2500000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
goal-weight: 0.4
epoch-num: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-layer-size: [256, 256]
dsr-gait-period: 0.6
rollout-step-num: 1
loss-output-diff-coeff: 0
max-path-step: 5000
env-id: HumanoidBalanceFilter-v0
LLC-frequency: 500
actor-layer-size: [256, 256]
reward-scale: 0.1
task-weight: 0.2
max-path-num: 20
prioritized-exp-replay: True
interpolation: False
filter-torque: False
critic-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
max-train-time: 10
state-dim: 25
actor-l2-reg: 0.0003
actor-lr: 0.0003
train-step-num: 1
loss-output-bound-coeff: 0.0
actor-weight-decay: 1e-06
critic-l2-reg: 0.0003
