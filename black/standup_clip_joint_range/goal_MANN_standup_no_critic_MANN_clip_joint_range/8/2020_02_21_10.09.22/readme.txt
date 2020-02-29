state-dim: 25
critic-weight-decay: 1e-06
tau: 0.001
loss-output-bound-coeff: 0.0
rollout-step-num: 1
critic-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
gating-layer-size: [128, 128]
actor-weight-decay: 1e-06
HLC-frequency: 25
max-train-time: 10
joint-interpolation: True
n-step: 1
actor-l2-reg: 0.0003
prioritized-exp-replay: True
critic-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
reward-scale: 0.1
actor-lr: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
action-dim: 12
max-test-time: 10
total-step-num: 2500000000
max-path-num: 20
batch-size: 128
gamma: 0.986
squash-action: True
max-episode-num: 5000000
epoch-step-num: 5000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
dsr-gait-freq: 1.667
env-id: HumanoidBalanceFilter-v0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
task-weight: 0.2
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
epoch-num: 500
max-path-step: 5000
max-step-num: 2500000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 8
render-eval: False
loss-output-diff-coeff: 0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
dsr-gait-period: 0.6
loss-output-smooth-coeff: 2.0
actor-activation-fn: ['relu', 'relu', 'None']
test-num: 4
record-start-size: 10000.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-ratio: 1
imitation-weight: 0.4
replay-buffer-size: 1000000
loss-entropy-coeff: 0.0
Physics-frequency: 1000
LLC-frequency: 500
critic-layer-size: [256, 256]
interpolation: False
bullet-default-PD: False
goal-weight: 0.4
critic-l2-reg: 0.0003
actor-layer-size: [256, 256]
filter-action: True
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
filter-torque: False
