critic-weight-decay: 1e-06
render-eval: False
critic-l2-reg: 0.0003
LLC-frequency: 500
Physics-frequency: 1000
actor-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
bullet-default-PD: False
max-train-time: 10
replay-ratio: 1
rollout-step-num: 1
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-output-bound-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
loss-output-diff-coeff: 0
gating-layer-size: [128, 128]
max-path-num: 20
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
train-step-num: 1
replay-start-size: 10000
loss-entropy-coeff: 0.0
prioritized-exp-replay: True
max-episode-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
goal-weight: 0.4
epoch-step-num: 5000000
interpolation: False
test-num: 4
critic-activation-fn: ['relu', 'relu', 'None']
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
loss-output-smooth-coeff: 2.0
actor-layer-size: [256, 256]
dsr-gait-period: 0.6
epoch-num: 500
tau: 0.001
actor-lr: 0.0003
critic-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
env-id: HumanoidBalanceFilter-v0
batch-size: 128
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
dsr-gait-freq: 1.667
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
task-weight: 0.2
expert-num: 8
max-path-step: 5000
filter-action: True
filter-torque: False
actor-l2-reg: 0.0003
state-dim: 25
replay-buffer-size: 1000000
HLC-frequency: 25
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
total-step-num: 2500000000
max-step-num: 2500000000
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
gamma: 0.986
max-test-time: 10
imitation-weight: 0.4
joint-interpolation: True
record-start-size: 10000.0
action-dim: 12
n-step: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
squash-action: True
