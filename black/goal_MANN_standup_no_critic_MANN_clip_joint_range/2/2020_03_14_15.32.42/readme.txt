max-path-num: 20
record-start-size: 10000.0
dsr-gait-freq: 1.667
LLC-frequency: 500
HLC-frequency: 25
filter-action: True
critic-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
render-eval: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-layer-size: [256, 256]
batch-size: 128
critic-lr: 0.0003
goal-weight: 0.4
total-step-num: 2500000000
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
critic-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
max-step-num: 2500000000
actor-l2-reg: 0.0003
filter-torque: False
max-path-step: 5000
replay-ratio: 1
rollout-step-num: 1
state-dim: 25
loss-output-diff-coeff: 0
joint-interpolation: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
reward-scale: 0.1
epoch-num: 500
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-lr: 0.0003
replay-buffer-size: 1000000
gating-layer-size: [128, 128]
max-train-time: 10
replay-start-size: 10000
critic-l2-reg: 0.0003
loss-output-smooth-coeff: 2.0
loss-output-bound-coeff: 0.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-weight-decay: 1e-06
interpolation: False
max-episode-num: 5000000
train-step-num: 1
dsr-gait-period: 0.6
test-num: 4
tau: 0.001
gamma: 0.986
epoch-step-num: 5000000
critic-weight-decay: 1e-06
action-dim: 12
bullet-default-PD: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-mask: [[1.0, 1.0]]
squash-action: True
max-test-time: 10
expert-num: 2
Physics-frequency: 1000
task-weight: 0.2
loss-entropy-coeff: 0.0
prioritized-exp-replay: True
actor-activation-fn: ['relu', 'relu', 'None']
n-step: 1
imitation-weight: 0.4
env-id: HumanoidBalanceFilter-v0
