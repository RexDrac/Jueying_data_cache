loss-output-diff-coeff: 0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
total-step-num: 2500000000
gamma: 0.986
loss-output-bound-coeff: 0.0
tau: 0.001
replay-buffer-size: 1000000
max-episode-num: 5000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
interpolation: False
max-path-step: 5000
record-start-size: 10000.0
actor-layer-size: [256, 256]
critic-l2-reg: 0.0003
task-weight: 0.5
loss-output-smooth-coeff: 1.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-freq: 1.667
max-path-num: 20
max-test-time: 10
critic-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
state-dim: 25
gating-layer-size: [128, 128]
imitation-weight: 0.5
actor-lr: 0.0003
HLC-frequency: 25
critic-weight-decay: 1e-06
joint-interpolation: True
critic-lr: 0.0003
max-train-time: 10
epoch-num: 500
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
filter-torque: False
max-step-num: 2500000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
prioritized-exp-replay: True
render-eval: False
train-step-num: 1
env-id: HumanoidBalanceFilter-v0
squash-action: True
test-num: 4
loss-entropy-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
n-step: 1
reward-scale: 0.1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-weight-decay: 1e-06
replay-ratio: 1
gating-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
LLC-frequency: 500
epoch-step-num: 5000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
replay-start-size: 10000
Physics-frequency: 1000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
batch-size: 128
dsr-gait-period: 0.6
critic-layer-size: [256, 256]
filter-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 8
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
