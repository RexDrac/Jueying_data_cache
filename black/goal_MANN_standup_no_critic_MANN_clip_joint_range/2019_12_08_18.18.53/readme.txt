normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-layer-size: [256, 256]
imitation-weight: 0.4
render-eval: False
test-num: 4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
dsr-gait-period: 0.6
Physics-frequency: 1000
replay-buffer-size: 1000000
bullet-default-PD: False
train-step-num: 1
actor-l2-reg: 0.0003
prioritized-exp-replay: True
critic-lr: 0.0003
expert-num: 8
goal-weight: 0.4
state-dim: 25
record-start-size: 10000.0
gamma: 0.986
loss-output-diff-coeff: 0
replay-ratio: 1
max-step-num: 2500000000
rollout-step-num: 1
dsr-gait-freq: 1.667
max-train-time: 10
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
action-dim: 12
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
total-step-num: 2500000000
loss-entropy-coeff: 0.0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
HLC-frequency: 25
replay-start-size: 10000
tau: 0.001
batch-size: 128
critic-l2-reg: 0.0003
filter-torque: False
epoch-num: 500
filter-action: True
gating-layer-size: [128, 128]
epoch-step-num: 5000000
loss-output-bound-coeff: 0.0
max-test-time: 10
env-id: HumanoidBalanceFilter-v0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 2.0
joint-interpolation: True
actor-layer-size: [256, 256]
squash-action: True
interpolation: False
critic-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.2
critic-weight-decay: 1e-06
actor-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-lr: 0.0003
LLC-frequency: 500
actor-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
n-step: 1
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
max-path-step: 5000
reward-scale: 0.1
