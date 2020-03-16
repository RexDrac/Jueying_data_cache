loss-entropy-coeff: 0.0
dsr-gait-period: 0.6
max-test-time: 10
state-dim: 25
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-ratio: 1
gamma: 0.986
critic-lr: 0.0003
HLC-frequency: 25
total-step-num: 2500000000
record-start-size: 10000.0
max-step-num: 2500000000
max-path-num: 20
test-num: 4
joint-interpolation: True
actor-layer-size: [256, 256]
prioritized-exp-replay: True
filter-torque: False
critic-layer-size: [256, 256]
actor-lr: 0.0003
max-episode-num: 5000000
critic-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
actor-l2-reg: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
filter-action: True
tau: 0.001
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
rollout-step-num: 1
LLC-frequency: 500
actor-weight-decay: 1e-06
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
epoch-step-num: 5000000
loss-output-diff-coeff: 0
interpolation: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
n-step: 1
epoch-num: 500
bullet-default-PD: False
dsr-gait-freq: 1.667
expert-num: 8
gating-layer-size: [128, 128]
reward-scale: 0.1
max-train-time: 10
Physics-frequency: 1000
squash-action: True
env-id: HumanoidBalanceFilter-v0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-path-step: 5000
critic-l2-reg: 0.0003
critic-weight-decay: 1e-06
action-dim: 12
loss-output-smooth-coeff: 2.0
replay-buffer-size: 1000000
goal-weight: 0.4
batch-size: 128
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
imitation-weight: 0.4
render-eval: False
task-weight: 0.2
gating-activation-fn: ['relu', 'relu', 'None']
