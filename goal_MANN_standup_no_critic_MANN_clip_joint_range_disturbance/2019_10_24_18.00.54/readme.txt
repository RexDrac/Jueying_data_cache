actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
train-step-num: 1
test-num: 4
dsr-gait-freq: 1.667
filter-torque: False
gating-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gamma: 0.986
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
render-eval: False
critic-weight-decay: 1e-06
replay-buffer-size: 1000000
replay-start-size: 10000
batch-size: 128
max-train-time: 10
max-test-time: 10
max-path-step: 5000
critic-l2-reg: 0.0003
record-start-size: 10000.0
env-id: HumanoidBalanceFilter-v0
dsr-gait-period: 0.6
LLC-frequency: 500
HLC-frequency: 25
state-dim: 25
action-dim: 12
squash-action: True
loss-output-bound-coeff: 0.0
rollout-step-num: 1
critic-activation-fn: ['relu', 'relu', 'None']
n-step: 1
max-step-num: 2500000000
bullet-default-PD: False
replay-ratio: 1
actor-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
imitation-weight: 0.5
task-weight: 0.5
max-episode-num: 5000000
critic-lr: 0.0003
total-step-num: 2500000000
loss-entropy-coeff: 0.0
expert-num: 8
actor-lr: 0.0003
loss-output-diff-coeff: 0
actor-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
actor-weight-decay: 1e-06
critic-layer-size: [256, 256]
epoch-step-num: 5000000
max-path-num: 20
actor-l2-reg: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
epoch-num: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
prioritized-exp-replay: True
joint-interpolation: True
tau: 0.001
interpolation: False
gating-layer-size: [128, 128]
loss-output-smooth-coeff: 1.0
