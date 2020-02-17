max-test-time: 10
max-path-num: 20
gamma: 0.986
gating-layer-size: [128, 128]
filter-action: True
task-weight: 0.2
env-id: HumanoidBalanceFilter-v0
max-episode-num: 5000000
action-dim: 12
HLC-frequency: 25
reward-scale: 0.1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
squash-action: True
n-step: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
goal-weight: 0.4
total-step-num: 2500000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
bullet-default-PD: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
critic-l2-reg: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
critic-layer-size: [256, 256]
imitation-weight: 0.4
interpolation: False
LLC-frequency: 500
loss-output-smooth-coeff: 2.0
expert-num: 8
joint-interpolation: True
record-start-size: 10000.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
filter-torque: False
replay-buffer-size: 1000000
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
render-eval: False
actor-layer-size: [256, 256]
test-num: 4
max-train-time: 10
Physics-frequency: 1000
actor-l2-reg: 0.0003
dsr-gait-freq: 1.667
loss-output-diff-coeff: 0
critic-lr: 0.0003
max-step-num: 2500000000
state-dim: 25
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-weight-decay: 1e-06
epoch-step-num: 5000000
loss-entropy-coeff: 0.0
actor-weight-decay: 1e-06
loss-output-bound-coeff: 0.0
train-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
rollout-step-num: 1
replay-ratio: 1
tau: 0.001
actor-lr: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
actor-activation-fn: ['relu', 'relu', 'None']
