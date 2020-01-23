bullet-default-PD: False
prioritized-exp-replay: True
max-path-step: 5000
loss-entropy-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-layer-size: [256, 256]
test-num: 4
batch-size: 128
expert-num: 8
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-start-size: 10000
task-weight: 0.2
gating-layer-size: [128, 128]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
n-step: 1
rollout-step-num: 1
max-test-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
epoch-num: 500
state-dim: 25
max-episode-num: 5000000
filter-torque: False
max-train-time: 10
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
action-dim: 12
LLC-frequency: 500
max-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
env-id: HumanoidBalanceFilter-v0
interpolation: False
dsr-gait-freq: 1.667
render-eval: False
imitation-weight: 0.4
reward-scale: 0.1
critic-l2-reg: 0.0003
loss-output-diff-coeff: 0
dsr-gait-period: 0.6
gamma: 0.986
goal-weight: 0.4
critic-lr: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
squash-action: True
epoch-step-num: 5000000
joint-interpolation: True
actor-l2-reg: 0.0003
total-step-num: 2500000000
replay-ratio: 1
tau: 0.001
gating-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
actor-lr: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-weight-decay: 1e-06
record-start-size: 10000.0
HLC-frequency: 25
train-step-num: 1
filter-action: True
Physics-frequency: 1000
loss-output-bound-coeff: 0.0
