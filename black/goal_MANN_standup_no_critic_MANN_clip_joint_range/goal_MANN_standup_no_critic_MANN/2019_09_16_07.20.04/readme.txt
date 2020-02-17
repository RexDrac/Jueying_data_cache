test-num: 4
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
epoch-step-num: 5000000
loss-output-bound-coeff: 0.0
n-step: 1
gamma: 0.955
dsr-gait-freq: 1.667
reward-scale: 0.1
HLC-frequency: 25
loss-output-diff-coeff: 0
loss-entropy-coeff: 0.0
gating-layer-size: [128, 128]
critic-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
joint-interpolation: True
loss-output-smooth-coeff: 2.0
replay-ratio: 1
replay-buffer-size: 1000000
epoch-num: 500
train-step-num: 1
max-test-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
filter-torque: False
Physics-frequency: 1000
interpolation: False
max-path-num: 20
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 25
expert-num: 8
critic-l2-reg: 0.0003
max-episode-num: 5000000
filter-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-weight-decay: 1e-06
squash-action: True
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
env-id: HumanoidBalanceFilter-v0
critic-layer-size: [256, 256]
actor-lr: 0.0003
imitation-weight: 0.5
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
action-dim: 12
rollout-step-num: 1
critic-lr: 0.0003
record-start-size: 10000.0
actor-layer-size: [256, 256]
bullet-default-PD: False
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
actor-l2-reg: 0.0003
max-train-time: 10
total-step-num: 2500000000
tau: 0.001
replay-start-size: 10000
max-step-num: 2500000000
prioritized-exp-replay: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
LLC-frequency: 500
task-weight: 0.5
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
batch-size: 128
actor-weight-decay: 1e-06
render-eval: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
