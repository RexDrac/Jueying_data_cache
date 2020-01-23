actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-weight-decay: 1e-06
actor-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
actor-l2-reg: 0.0003
test-num: 4
max-episode-num: 5000000
n-step: 1
loss-output-bound-coeff: 0.0
filter-action: True
epoch-step-num: 5000000
replay-buffer-size: 1000000
train-step-num: 1
epoch-num: 500
loss-entropy-coeff: 0.0
filter-torque: False
joint-interpolation: True
interpolation: False
gating-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
imitation-weight: 0.5
dsr-gait-freq: 1.667
replay-ratio: 1
rollout-step-num: 1
record-start-size: 10000.0
expert-num: 8
env-id: HumanoidBalanceFilter-v0
task-weight: 0.5
Physics-frequency: 1000
squash-action: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-weight-decay: 1e-06
loss-output-diff-coeff: 0
critic-lr: 0.0003
gating-layer-size: [128, 128]
HLC-frequency: 25
critic-layer-size: [256, 256]
max-step-num: 2500000000
loss-output-smooth-coeff: 1.0
replay-start-size: 10000
LLC-frequency: 500
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
max-train-time: 10
state-dim: 25
batch-size: 128
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-period: 0.6
max-test-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
total-step-num: 2500000000
render-eval: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
action-dim: 12
actor-lr: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
prioritized-exp-replay: True
gamma: 0.95
bullet-default-PD: False
critic-activation-fn: ['relu', 'relu', 'None']
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-path-num: 20
max-path-step: 5000
critic-l2-reg: 0.0003
tau: 0.001
