render-eval: False
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
LLC-frequency: 500
record-start-size: 10000.0
actor-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
loss-output-bound-coeff: 0.0
replay-buffer-size: 1000000
action-dim: 12
loss-entropy-coeff: 0.0
filter-torque: False
tau: 0.001
env-id: HumanoidBalanceFilter-v0
critic-l2-reg: 0.0003
max-train-time: 10
n-step: 1
batch-size: 128
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-ratio: 1
max-path-num: 20
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
HLC-frequency: 25
filter-action: True
replay-start-size: 10000
state-dim: 25
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
epoch-step-num: 5000000
interpolation: False
loss-output-diff-coeff: 0
rollout-step-num: 1
prioritized-exp-replay: True
max-test-time: 10
epoch-num: 500
critic-weight-decay: 1e-06
train-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
dsr-gait-freq: 1.667
actor-weight-decay: 1e-06
gating-layer-size: [128, 128]
gamma: 0.986
Physics-frequency: 1000
expert-num: 8
total-step-num: 2500000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-period: 0.6
task-weight: 0.0
squash-action: True
max-episode-num: 5000000
bullet-default-PD: False
max-step-num: 2500000000
critic-layer-size: [256, 256]
imitation-weight: 0.5
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
actor-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
goal-weight: 0.5
max-path-step: 5000
actor-layer-size: [256, 256]
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
critic-activation-fn: ['relu', 'relu', 'None']
test-num: 4
