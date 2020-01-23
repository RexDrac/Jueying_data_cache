actor-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
HLC-frequency: 25
imitation-weight: 0.4
dsr-gait-freq: 1.667
replay-buffer-size: 1000000
gamma: 0.986
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
replay-ratio: 1
critic-l2-reg: 0.0003
actor-weight-decay: 1e-06
tau: 0.001
gating-layer-size: [128, 128]
critic-activation-fn: ['relu', 'relu', 'None']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
interpolation: False
task-weight: 0.2
max-step-num: 2500000000
batch-size: 128
filter-torque: False
loss-output-diff-coeff: 0
reward-scale: 0.1
expert-num: 8
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
epoch-step-num: 5000000
n-step: 1
state-dim: 25
max-test-time: 10
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-path-num: 20
loss-entropy-coeff: 0.0
loss-output-smooth-coeff: 2.0
env-id: HumanoidBalanceFilter-v0
actor-lr: 0.0003
LLC-frequency: 500
max-train-time: 10
goal-weight: 0.4
critic-weight-decay: 1e-06
filter-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
epoch-num: 500
dsr-gait-period: 0.6
train-step-num: 1
render-eval: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
total-step-num: 2500000000
test-num: 4
replay-start-size: 10000
critic-lr: 0.0003
critic-layer-size: [256, 256]
Physics-frequency: 1000
rollout-step-num: 1
actor-l2-reg: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
prioritized-exp-replay: True
record-start-size: 10000.0
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
actor-layer-size: [256, 256]
squash-action: True
joint-interpolation: True
max-episode-num: 5000000
max-path-step: 5000
