Physics-frequency: 1000
critic-l2-reg: 0.0003
interpolation: False
max-test-time: 10
prioritized-exp-replay: True
replay-ratio: 1
gating-activation-fn: ['relu', 'relu', 'None']
critic-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
critic-weight-decay: 1e-06
reward-scale: 0.1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
max-step-num: 2500000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-train-time: 10
loss-entropy-coeff: 0.0
loss-output-bound-coeff: 0.0
filter-torque: False
replay-buffer-size: 1000000
goal-weight: 0.4
loss-output-diff-coeff: 0
n-step: 1
task-weight: 0.2
epoch-num: 500
actor-layer-size: [256, 256]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
imitation-weight: 0.4
tau: 0.001
squash-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gamma: 0.986
dsr-gait-freq: 1.667
actor-weight-decay: 1e-06
expert-num: 8
epoch-step-num: 5000000
train-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
rollout-step-num: 1
replay-start-size: 10000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
env-id: HumanoidBalanceFilter-v0
gating-layer-size: [128, 128]
state-dim: 25
test-num: 4
critic-lr: 0.0003
max-path-num: 20
HLC-frequency: 25
action-dim: 12
render-eval: False
bullet-default-PD: False
actor-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
record-start-size: 10000.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
LLC-frequency: 500
loss-output-smooth-coeff: 2.0
max-episode-num: 5000000
actor-l2-reg: 0.0003
joint-interpolation: True
critic-layer-size: [256, 256]
dsr-gait-period: 0.6
total-step-num: 2500000000
filter-action: True
actor-lr: 0.0003
