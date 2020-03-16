actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-ratio: 1
critic-weight-decay: 1e-06
actor-activation-fn: ['relu', 'relu', 'None']
max-test-time: 10
max-path-step: 5000
actor-lr: 0.0003
test-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
max-train-time: 10
task-weight: 0.2
loss-output-diff-coeff: 0
actor-weight-decay: 1e-06
gamma: 0.986
loss-output-bound-coeff: 0.0
gating-layer-size: [128, 128]
replay-start-size: 10000
reward-scale: 0.1
critic-l2-reg: 0.0003
rollout-step-num: 1
max-episode-num: 5000000
actor-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
Physics-frequency: 1000
joint-interpolation: True
LLC-frequency: 500
dsr-gait-period: 0.6
actor-layer-size: [256, 256]
filter-action: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
squash-action: True
loss-output-smooth-coeff: 2.0
env-id: HumanoidBalanceFilter-v0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
state-dim: 25
bullet-default-PD: False
expert-num: 8
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
critic-lr: 0.0003
batch-size: 128
epoch-step-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
epoch-num: 500
render-eval: False
prioritized-exp-replay: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
interpolation: False
dsr-gait-freq: 1.667
goal-weight: 0.4
total-step-num: 2500000000
loss-entropy-coeff: 0.0
max-step-num: 2500000000
replay-buffer-size: 1000000
record-start-size: 10000.0
n-step: 1
filter-torque: False
action-dim: 12
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
HLC-frequency: 25
tau: 0.001
imitation-weight: 0.4
critic-activation-fn: ['relu', 'relu', 'None']
