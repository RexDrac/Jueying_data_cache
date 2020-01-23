task-weight: 0.2
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
filter-torque: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
imitation-weight: 0.4
tau: 0.001
critic-l2-reg: 0.0003
replay-ratio: 1
total-step-num: 2500000000
max-path-step: 5000
actor-weight-decay: 1e-06
state-dim: 25
critic-weight-decay: 1e-06
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
max-train-time: 10
critic-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
critic-layer-size: [256, 256]
reward-scale: 0.1
replay-buffer-size: 1000000
actor-layer-size: [256, 256]
loss-entropy-coeff: 0.0
interpolation: False
expert-num: 8
n-step: 1
squash-action: True
prioritized-exp-replay: True
critic-lr: 0.0003
max-episode-num: 5000000
LLC-frequency: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
max-test-time: 10
train-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
joint-interpolation: True
loss-output-bound-coeff: 0.0
record-start-size: 10000.0
replay-start-size: 10000
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
epoch-num: 500
max-step-num: 2500000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
test-num: 4
filter-action: True
env-id: HumanoidBalanceFilter-v0
gamma: 0.997
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
dsr-gait-period: 0.6
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
Physics-frequency: 1000
render-eval: False
HLC-frequency: 100
loss-output-diff-coeff: 0
loss-output-smooth-coeff: 2.0
gating-layer-size: [128, 128]
dsr-gait-freq: 1.667
epoch-step-num: 5000000
bullet-default-PD: False
goal-weight: 0.4
action-dim: 12
batch-size: 128
gating-activation-fn: ['relu', 'relu', 'None']
