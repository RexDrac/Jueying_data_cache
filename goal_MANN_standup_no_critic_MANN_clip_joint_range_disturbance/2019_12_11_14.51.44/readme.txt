actor-layer-size: [256, 256]
max-path-step: 5000
max-episode-num: 5000000
dsr-gait-freq: 1.667
squash-action: True
LLC-frequency: 500
epoch-step-num: 5000000
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
gating-layer-size: [128, 128]
interpolation: False
rollout-step-num: 1
loss-output-smooth-coeff: 2.0
prioritized-exp-replay: True
gamma: 0.986
actor-lr: 0.0003
loss-output-bound-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
expert-num: 8
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
imitation-weight: 0.4
max-test-time: 10
replay-start-size: 10000
bullet-default-PD: False
replay-buffer-size: 1000000
joint-interpolation: True
actor-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-ratio: 1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
n-step: 1
loss-output-diff-coeff: 0
max-step-num: 2500000000
task-weight: 0.2
render-eval: False
Physics-frequency: 1000
critic-weight-decay: 1e-06
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
epoch-num: 500
filter-action: True
train-step-num: 1
reward-scale: 0.1
record-start-size: 10000.0
critic-layer-size: [256, 256]
max-path-num: 20
env-id: HumanoidBalanceFilter-v0
HLC-frequency: 25
critic-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
critic-lr: 0.0003
state-dim: 25
max-train-time: 10
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
loss-entropy-coeff: 0.0
dsr-gait-period: 0.6
filter-torque: False
total-step-num: 2500000000
test-num: 4
action-dim: 12
goal-weight: 0.4
