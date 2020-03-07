controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
train-step-num: 1
critic-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
filter-torque: False
imitation-weight: 0.4
test-num: 4
HLC-frequency: 25
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-train-time: 10
squash-action: True
reward-scale: 0.1
action-dim: 12
dsr-gait-period: 0.6
bullet-default-PD: False
record-start-size: 10000.0
actor-layer-size: [256, 256]
total-step-num: 2500000000
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
loss-output-diff-coeff: 0
batch-size: 128
epoch-step-num: 5000000
dsr-gait-freq: 1.667
n-step: 1
LLC-frequency: 500
replay-ratio: 1
gamma: 0.986
epoch-num: 500
max-path-step: 5000
replay-buffer-size: 1000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-lr: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
task-weight: 0.2
render-eval: False
max-path-num: 20
tau: 0.001
joint-interpolation: True
gating-layer-size: [128, 128]
actor-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
expert-num: 8
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
prioritized-exp-replay: True
env-id: HumanoidBalanceFilter-v0
gating-activation-fn: ['relu', 'relu', 'None']
state-dim: 25
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
goal-weight: 0.4
rollout-step-num: 1
Physics-frequency: 1000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-lr: 0.0003
loss-entropy-coeff: 0.0
interpolation: False
filter-action: True
max-episode-num: 5000000
max-test-time: 10
actor-weight-decay: 1e-06
max-step-num: 2500000000
critic-l2-reg: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
