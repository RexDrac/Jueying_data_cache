joint-interpolation: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
reward-scale: 0.1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
train-step-num: 1
prioritized-exp-replay: True
critic-weight-decay: 1e-06
actor-l2-reg: 0.0003
LLC-frequency: 500
loss-output-diff-coeff: 0
filter-action: True
replay-buffer-size: 1000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
action-dim: 12
render-eval: False
max-path-num: 20
loss-output-bound-coeff: 0.0
expert-num: 8
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
replay-start-size: 10000
rollout-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
batch-size: 128
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
interpolation: False
loss-entropy-coeff: 0.0
critic-layer-size: [256, 256]
bullet-default-PD: False
actor-layer-size: [256, 256]
task-weight: 0.2
dsr-gait-period: 0.6
tau: 0.001
state-dim: 25
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-l2-reg: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
goal-weight: 0.6
epoch-num: 500
total-step-num: 2500000000
gating-layer-size: [128, 128]
epoch-step-num: 5000000
imitation-weight: 0.2
gamma: 0.986
test-num: 4
squash-action: True
record-start-size: 10000.0
max-test-time: 10
critic-lr: 0.0003
actor-weight-decay: 1e-06
max-path-step: 5000
max-train-time: 10
env-id: HumanoidBalanceFilter-v0
n-step: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
dsr-gait-freq: 1.667
Physics-frequency: 1000
max-episode-num: 5000000
max-step-num: 2500000000
actor-lr: 0.0003
