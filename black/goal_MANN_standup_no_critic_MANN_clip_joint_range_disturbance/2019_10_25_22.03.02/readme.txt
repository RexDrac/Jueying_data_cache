joint-interpolation: True
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
render-eval: False
state-dim: 25
filter-torque: False
gating-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
gamma: 0.986
epoch-num: 500
max-step-num: 2500000000
gating-layer-size: [128, 128]
env-id: HumanoidBalanceFilter-v0
actor-weight-decay: 1e-06
goal-weight: 0.4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
total-step-num: 2500000000
prioritized-exp-replay: True
LLC-frequency: 500
HLC-frequency: 25
actor-l2-reg: 0.0003
epoch-step-num: 5000000
filter-action: True
reward-scale: 0.1
replay-start-size: 10000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
imitation-weight: 0.3
critic-l2-reg: 0.0003
test-num: 4
critic-layer-size: [256, 256]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
batch-size: 128
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
loss-entropy-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
interpolation: False
loss-output-bound-coeff: 0.0
max-path-step: 5000
max-path-num: 20
expert-num: 8
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
loss-output-diff-coeff: 0
tau: 0.001
max-episode-num: 5000000
replay-ratio: 1
actor-layer-size: [256, 256]
dsr-gait-freq: 1.667
loss-output-smooth-coeff: 1.0
rollout-step-num: 1
max-test-time: 10
Physics-frequency: 1000
squash-action: True
critic-weight-decay: 1e-06
action-dim: 12
replay-buffer-size: 1000000
actor-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
actor-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
task-weight: 0.3
