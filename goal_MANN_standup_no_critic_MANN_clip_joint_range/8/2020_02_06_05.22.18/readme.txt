replay-ratio: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-period: 0.6
squash-action: True
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
epoch-step-num: 5000000
loss-output-smooth-coeff: 2.0
Physics-frequency: 1000
train-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gamma: 0.986
prioritized-exp-replay: True
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-torque: False
rollout-step-num: 1
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
state-dim: 25
filter-action: True
critic-weight-decay: 1e-06
max-path-step: 5000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
actor-weight-decay: 1e-06
HLC-frequency: 25
total-step-num: 2500000000
actor-layer-size: [256, 256]
imitation-weight: 0.4
critic-lr: 0.0003
max-path-num: 20
tau: 0.001
loss-entropy-coeff: 0.0
expert-num: 8
max-step-num: 2500000000
loss-output-diff-coeff: 0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-l2-reg: 0.0003
max-test-time: 10
epoch-num: 500
gating-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
test-num: 4
gating-layer-size: [128, 128]
max-train-time: 10
joint-interpolation: True
dsr-gait-freq: 1.667
replay-start-size: 10000
reward-scale: 0.1
render-eval: False
task-weight: 0.2
loss-output-bound-coeff: 0.0
goal-weight: 0.4
replay-buffer-size: 1000000
env-id: HumanoidBalanceFilter-v0
critic-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
LLC-frequency: 500
action-dim: 12
actor-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
interpolation: False
bullet-default-PD: False
critic-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
n-step: 1
critic-layer-size: [256, 256]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
