max-train-time: 10
tau: 0.001
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
prioritized-exp-replay: True
epoch-num: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
gating-layer-size: [128, 128]
reward-scale: 0.1
gamma: 0.955
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-torque: False
loss-output-bound-coeff: 0.0
train-step-num: 1
actor-l2-reg: 0.0003
dsr-gait-period: 0.6
max-step-num: 2500000000
max-path-step: 5000
record-start-size: 10000.0
dsr-gait-freq: 1.667
n-step: 1
loss-output-diff-coeff: 0
max-episode-num: 5000000
actor-weight-decay: 1e-06
task-weight: 0.5
squash-action: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
state-dim: 25
critic-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
imitation-weight: 0.5
Physics-frequency: 1000
test-num: 4
filter-action: True
interpolation: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
expert-num: 8
epoch-step-num: 5000000
replay-start-size: 10000
actor-lr: 0.0003
batch-size: 128
joint-interpolation: True
loss-entropy-coeff: 0.0
action-dim: 12
critic-layer-size: [256, 256]
critic-lr: 0.0003
loss-output-smooth-coeff: 2.0
LLC-frequency: 500
max-test-time: 10
total-step-num: 2500000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
replay-ratio: 1
critic-l2-reg: 0.0003
max-path-num: 20
rollout-step-num: 1
render-eval: False
replay-buffer-size: 1000000
actor-layer-size: [256, 256]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-activation-fn: ['relu', 'relu', 'None']
