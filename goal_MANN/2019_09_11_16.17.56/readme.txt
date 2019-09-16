render-eval: False
Physics-frequency: 1000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-episode-num: 5000000
gamma: 0.955
actor-l2-reg: 0.0003
n-step: 1
total-step-num: 2500000000
max-path-step: 5000
actor-lr: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
dsr-gait-freq: 1.667
critic-layer-size: [256, 256]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
reward-scale: 0.1
critic-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
task-weight: 0.5
dsr-gait-period: 0.6
replay-ratio: 1
batch-size: 128
prioritized-exp-replay: True
loss-output-diff-coeff: 0
replay-buffer-size: 1000000
joint-interpolation: True
squash-action: True
loss-output-smooth-coeff: 1.0
train-step-num: 1
gating-layer-size: [128, 128]
bullet-default-PD: False
actor-activation-fn: ['relu', 'relu', 'None']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
max-test-time: 10
rollout-step-num: 1
state-dim: 25
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-weight-decay: 1e-06
LLC-frequency: 500
env-id: HumanoidBalanceFilter-v0
test-num: 4
critic-l2-reg: 0.0003
interpolation: False
gating-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
HLC-frequency: 25
filter-action: True
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
max-path-num: 20
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
critic-lr: 0.0003
imitation-weight: 0.5
max-step-num: 2500000000
filter-torque: False
tau: 0.001
epoch-num: 500
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-layer-size: [256, 256]
loss-entropy-coeff: 0.0
replay-start-size: 10000
loss-output-bound-coeff: 0.0
actor-weight-decay: 1e-06
expert-num: 4
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
