loss-output-smooth-coeff: 2.0
total-step-num: 2500000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
joint-interpolation: True
Physics-frequency: 1000
HLC-frequency: 25
replay-start-size: 10000
loss-output-diff-coeff: 0
squash-action: True
max-train-time: 10
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
goal-weight: 0.4
interpolation: False
gating-layer-size: [128, 128]
reward-scale: 0.1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-layer-size: [256, 256]
env-id: HumanoidBalanceFilter-v0
imitation-weight: 0.4
task-weight: 0.2
dsr-gait-freq: 1.667
n-step: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
loss-output-bound-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
expert-num: 8
critic-lr: 0.0003
critic-layer-size: [256, 256]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
rollout-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
max-test-time: 10
LLC-frequency: 500
replay-ratio: 1
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
action-dim: 12
gamma: 0.986
critic-weight-decay: 1e-06
replay-buffer-size: 1000000
gating-activation-fn: ['relu', 'relu', 'None']
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
epoch-step-num: 5000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
filter-action: True
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
max-step-num: 2500000000
bullet-default-PD: False
state-dim: 25
epoch-num: 500
actor-lr: 0.0003
actor-weight-decay: 1e-06
train-step-num: 1
tau: 0.001
max-path-step: 5000
loss-entropy-coeff: 0.0
prioritized-exp-replay: True
dsr-gait-period: 0.6
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-episode-num: 5000000
test-num: 4
render-eval: False
max-path-num: 20
record-start-size: 10000.0
actor-l2-reg: 0.0003
