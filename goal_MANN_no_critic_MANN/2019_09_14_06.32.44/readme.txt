total-step-num: 2500000000
rollout-step-num: 1
replay-start-size: 10000
env-id: HumanoidBalanceFilter-v0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
record-start-size: 10000.0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
filter-torque: False
max-path-step: 5000
render-eval: False
actor-l2-reg: 0.0003
filter-action: True
actor-lr: 0.0003
critic-layer-size: [256, 256]
epoch-step-num: 5000000
joint-interpolation: True
gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
actor-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
max-episode-num: 5000000
gamma: 0.955
gating-layer-size: [128, 128]
tau: 0.001
critic-lr: 0.0003
actor-weight-decay: 1e-06
interpolation: False
LLC-frequency: 500
dsr-gait-freq: 1.667
critic-weight-decay: 1e-06
action-dim: 12
loss-output-smooth-coeff: 1.0
critic-l2-reg: 0.0003
max-train-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-period: 0.6
Physics-frequency: 1000
loss-output-diff-coeff: 0
actor-layer-size: [256, 256]
loss-output-bound-coeff: 0.0
replay-ratio: 1
state-dim: 25
squash-action: True
bullet-default-PD: False
prioritized-exp-replay: True
imitation-weight: 0.5
max-test-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
replay-buffer-size: 1000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
n-step: 1
max-step-num: 2500000000
task-weight: 0.5
HLC-frequency: 25
max-path-num: 20
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
loss-entropy-coeff: 0.0
expert-num: 4
epoch-num: 500
