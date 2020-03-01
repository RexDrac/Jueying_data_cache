gamma: 0.986
bullet-default-PD: False
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-layer-size: [256, 256]
state-dim: 25
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
max-path-num: 20
max-path-step: 5000
max-test-time: 10
action-dim: 12
filter-torque: False
replay-start-size: 10000
test-num: 4
task-weight: 0.2
dsr-gait-freq: 1.667
actor-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
prioritized-exp-replay: True
expert-num: 8
total-step-num: 2500000000
max-step-num: 2500000000
goal-weight: 0.4
HLC-frequency: 25
filter-action: True
actor-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
squash-action: True
train-step-num: 1
record-start-size: 10000.0
critic-l2-reg: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
actor-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
n-step: 1
loss-entropy-coeff: 0.0
epoch-num: 500
critic-activation-fn: ['relu', 'relu', 'None']
interpolation: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
rollout-step-num: 1
env-id: HumanoidBalanceFilter-v0
actor-lr: 0.0003
critic-lr: 0.0003
LLC-frequency: 500
max-episode-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-diff-coeff: 0
joint-interpolation: True
replay-buffer-size: 1000000
reward-scale: 0.1
tau: 0.001
epoch-step-num: 5000000
Physics-frequency: 1000
batch-size: 128
imitation-weight: 0.4
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-ratio: 1
loss-output-bound-coeff: 0.0
render-eval: False
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
dsr-gait-period: 0.6
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-layer-size: [128, 128]
critic-layer-size: [256, 256]
loss-output-smooth-coeff: 2.0
