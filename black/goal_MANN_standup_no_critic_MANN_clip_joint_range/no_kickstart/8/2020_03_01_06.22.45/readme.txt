test-num: 4
Physics-frequency: 1000
action-dim: 12
filter-torque: False
max-step-num: 2500000000
goal-weight: 0.4
actor-lr: 0.0003
train-step-num: 1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-weight-decay: 1e-06
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-buffer-size: 1000000
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
dsr-gait-period: 0.6
gamma: 0.986
max-test-time: 10
n-step: 1
interpolation: False
LLC-frequency: 500
replay-ratio: 1
critic-lr: 0.0003
loss-output-bound-coeff: 0.0
actor-layer-size: [256, 256]
batch-size: 128
gating-layer-size: [128, 128]
task-weight: 0.2
actor-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
loss-output-diff-coeff: 0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
squash-action: True
prioritized-exp-replay: True
reward-scale: 0.1
dsr-gait-freq: 1.667
max-path-num: 20
record-start-size: 10000.0
max-path-step: 5000
critic-weight-decay: 1e-06
state-dim: 25
critic-l2-reg: 0.0003
joint-interpolation: True
gating-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
total-step-num: 2500000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
critic-layer-size: [256, 256]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
replay-start-size: 10000
rollout-step-num: 1
imitation-weight: 0.4
render-eval: False
bullet-default-PD: False
max-episode-num: 5000000
epoch-num: 500
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
max-train-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-entropy-coeff: 0.0
loss-output-smooth-coeff: 2.0
filter-action: True
tau: 0.001
expert-num: 8
