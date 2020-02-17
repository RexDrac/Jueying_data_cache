expert-num: 8
reward-scale: 0.1
dsr-gait-period: 0.6
LLC-frequency: 500
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
max-step-num: 2500000000
max-path-num: 20
prioritized-exp-replay: True
max-train-time: 10
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-path-step: 5000
replay-ratio: 1
batch-size: 128
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-test-time: 10
gamma: 0.986
critic-lr: 0.0003
state-dim: 25
task-weight: 0.2
critic-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-lr: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
loss-output-diff-coeff: 0
actor-weight-decay: 1e-06
gating-layer-size: [128, 128]
record-start-size: 10000.0
train-step-num: 1
squash-action: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-torque: False
HLC-frequency: 25
epoch-num: 500
dsr-gait-freq: 1.667
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
rollout-step-num: 1
critic-l2-reg: 0.0003
action-dim: 12
epoch-step-num: 5000000
loss-output-smooth-coeff: 2.0
max-episode-num: 5000000
filter-action: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
total-step-num: 2500000000
critic-layer-size: [256, 256]
actor-activation-fn: ['relu', 'relu', 'None']
test-num: 4
goal-weight: 0.4
n-step: 1
tau: 0.001
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-buffer-size: 1000000
actor-layer-size: [256, 256]
Physics-frequency: 1000
replay-start-size: 10000
env-id: HumanoidBalanceFilter-v0
render-eval: False
actor-l2-reg: 0.0003
joint-interpolation: True
bullet-default-PD: False
gating-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
imitation-weight: 0.4
interpolation: False
