gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
train-step-num: 1
render-eval: False
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
record-start-size: 10000.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-start-size: 10000
bullet-default-PD: False
dsr-gait-freq: 1.667
max-episode-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [128, 128]
dsr-gait-period: 0.6
LLC-frequency: 500
gamma: 0.997
max-test-time: 10
loss-output-smooth-coeff: 8.0
squash-action: True
filter-action: True
critic-l2-reg: 0.0003
critic-weight-decay: 1e-06
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
HLC-frequency: 100
loss-output-diff-coeff: 0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
action-dim: 12
critic-lr: 0.0003
reward-scale: 0.1
replay-ratio: 1
epoch-num: 500
n-step: 1
loss-entropy-coeff: 0.0
test-num: 4
task-weight: 0.2
Physics-frequency: 1000
loss-output-bound-coeff: 0.0
interpolation: False
env-id: HumanoidBalanceFilter-v0
critic-layer-size: [256, 256]
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
goal-weight: 0.4
joint-interpolation: True
actor-lr: 0.0003
tau: 0.001
filter-torque: False
max-train-time: 10
prioritized-exp-replay: True
batch-size: 128
actor-weight-decay: 1e-06
max-path-step: 5000
critic-activation-fn: ['relu', 'relu', 'None']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
total-step-num: 2500000000
actor-layer-size: [256, 256]
max-path-num: 20
state-dim: 25
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
epoch-step-num: 5000000
max-step-num: 2500000000
expert-num: 8
imitation-weight: 0.4
rollout-step-num: 1
