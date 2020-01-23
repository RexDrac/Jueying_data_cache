batch-size: 128
env-id: HumanoidBalanceFilter-v0
filter-action: True
epoch-num: 500
record-start-size: 10000.0
actor-l2-reg: 0.0003
max-path-step: 5000
squash-action: True
actor-layer-size: [256, 256]
gating-layer-size: [128, 128]
filter-torque: False
render-eval: False
train-step-num: 1
task-weight: 0.3
loss-output-bound-coeff: 0.0
n-step: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
prioritized-exp-replay: True
HLC-frequency: 25
max-test-time: 10
critic-layer-size: [256, 256]
max-episode-num: 5000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
joint-interpolation: True
action-dim: 12
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
Physics-frequency: 1000
imitation-weight: 0.3
LLC-frequency: 500
epoch-step-num: 5000000
reward-scale: 0.1
total-step-num: 2500000000
test-num: 4
tau: 0.001
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-diff-coeff: 0
max-path-num: 20
loss-entropy-coeff: 0.0
gamma: 0.986
gating-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
loss-output-smooth-coeff: 2.0
critic-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-buffer-size: 1000000
critic-weight-decay: 1e-06
bullet-default-PD: False
expert-num: 8
dsr-gait-freq: 1.667
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-ratio: 1
max-step-num: 2500000000
goal-weight: 0.4
max-train-time: 10
critic-lr: 0.0003
replay-start-size: 10000
actor-activation-fn: ['relu', 'relu', 'None']
state-dim: 25
actor-lr: 0.0003
interpolation: False
dsr-gait-period: 0.6
rollout-step-num: 1
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-weight-decay: 1e-06
