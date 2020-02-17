reward-scale: 0.1
replay-buffer-size: 1000000
env-id: HumanoidBalanceFilter-v0
replay-start-size: 10000
LLC-frequency: 500
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
test-num: 4
max-step-num: 2500000000
total-step-num: 2500000000
actor-l2-reg: 0.0003
epoch-num: 500
bullet-default-PD: False
actor-layer-size: [256, 256]
record-start-size: 10000.0
batch-size: 128
gamma: 0.986
gating-layer-size: [128, 128]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-lr: 0.0003
train-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
imitation-weight: 0.4
action-dim: 12
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
filter-action: True
critic-layer-size: [256, 256]
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
goal-weight: 0.4
dsr-gait-freq: 1.667
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
epoch-step-num: 5000000
actor-weight-decay: 1e-06
tau: 0.001
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
critic-l2-reg: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
state-dim: 25
loss-entropy-coeff: 0.0
max-test-time: 10
interpolation: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-ratio: 1
HLC-frequency: 25
rollout-step-num: 1
squash-action: True
dsr-gait-period: 0.6
actor-lr: 0.0003
expert-num: 6
max-path-step: 5000
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-episode-num: 5000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
task-weight: 0.2
loss-output-diff-coeff: 0
prioritized-exp-replay: True
critic-weight-decay: 1e-06
n-step: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-num: 20
Physics-frequency: 1000
render-eval: False
