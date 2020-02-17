actor-layer-size: [256, 256]
max-path-step: 5000
filter-torque: False
gamma: 0.95
critic-layer-size: [256, 256]
test-num: 4
max-episode-num: 5000000
filter-action: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
train-step-num: 1
loss-output-bound-coeff: 0.0
replay-start-size: 10000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
epoch-step-num: 5000000
max-path-num: 20
Physics-frequency: 1000
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
critic-lr: 0.0003
render-eval: False
imitation-weight: 0.5
max-step-num: 2500000000
action-dim: 12
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
n-step: 1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
total-step-num: 2500000000
rollout-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
reward-scale: 0.1
dsr-gait-period: 0.6
interpolation: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.5
critic-weight-decay: 1e-06
replay-ratio: 1
max-test-time: 10
actor-lr: 0.0003
joint-interpolation: True
expert-num: 8
LLC-frequency: 500
actor-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
batch-size: 128
replay-buffer-size: 1000000
gating-layer-size: [128, 128]
loss-output-diff-coeff: 0
loss-entropy-coeff: 0.0
epoch-num: 500
squash-action: True
prioritized-exp-replay: True
loss-output-smooth-coeff: 1.0
actor-l2-reg: 0.0003
actor-weight-decay: 1e-06
critic-l2-reg: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
state-dim: 25
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
bullet-default-PD: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
dsr-gait-freq: 1.667
HLC-frequency: 25
