tau: 0.001
dsr-gait-freq: 1.667
total-step-num: 2500000000
rollout-step-num: 1
actor-l2-reg: 0.0003
render-eval: False
squash-action: True
max-test-time: 10
max-episode-num: 5000000
replay-buffer-size: 1000000
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
joint-interpolation: True
n-step: 1
actor-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-step-num: 2500000000
max-train-time: 10
bullet-default-PD: False
critic-lr: 0.0003
expert-num: 8
max-path-num: 20
critic-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
dsr-gait-period: 0.6
gamma: 0.986
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
loss-entropy-coeff: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-ratio: 1
gating-layer-size: [128, 128]
Physics-frequency: 1000
actor-lr: 0.0003
state-dim: 25
env-id: HumanoidBalanceFilter-v0
train-step-num: 1
filter-torque: False
filter-action: True
LLC-frequency: 500
gating-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.0
reward-scale: 0.1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-activation-fn: ['relu', 'relu', 'None']
interpolation: False
max-path-step: 5000
replay-start-size: 10000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
imitation-weight: 0.5
loss-output-diff-coeff: 0
goal-weight: 0.5
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-num: 500
actor-weight-decay: 1e-06
prioritized-exp-replay: True
loss-output-bound-coeff: 0.0
action-dim: 12
test-num: 4
critic-weight-decay: 1e-06
record-start-size: 10000.0
HLC-frequency: 25
critic-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
batch-size: 128
loss-output-smooth-coeff: 2.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
