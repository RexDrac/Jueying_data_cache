gating-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
interpolation: False
expert-num: 4
max-test-time: 10
tau: 0.001
replay-buffer-size: 1000000
state-dim: 25
loss-output-bound-coeff: 0.0
actor-weight-decay: 1e-06
max-path-step: 5000
reward-scale: 0.1
LLC-frequency: 500
gating-layer-size: [128, 128]
joint-interpolation: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
goal-weight: 0.4
max-train-time: 10
train-step-num: 1
max-step-num: 2500000000
actor-l2-reg: 0.0003
render-eval: False
bullet-default-PD: False
HLC-frequency: 25
max-episode-num: 5000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-step-num: 5000000
actor-layer-size: [256, 256]
epoch-num: 500
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
filter-torque: False
actor-lr: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
loss-output-smooth-coeff: 2.0
record-start-size: 10000.0
critic-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
critic-layer-size: [256, 256]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
max-path-num: 20
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
env-id: HumanoidBalanceFilter-v0
replay-start-size: 10000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-entropy-coeff: 0.0
gamma: 0.986
gating-mask: [[1.0, 1.0, 1.0, 1.0]]
test-num: 4
replay-ratio: 1
loss-output-diff-coeff: 0
task-weight: 0.2
dsr-gait-period: 0.6
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
squash-action: True
critic-l2-reg: 0.0003
Physics-frequency: 1000
imitation-weight: 0.4
dsr-gait-freq: 1.667
n-step: 1
prioritized-exp-replay: True
actor-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
critic-lr: 0.0003
batch-size: 128
