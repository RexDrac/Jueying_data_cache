goal-weight: 0.4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
max-step-num: 2500000000
render-eval: False
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
actor-layer-size: [256, 256]
test-num: 4
loss-output-bound-coeff: 0.0
gamma: 0.986
imitation-weight: 0.3
state-dim: 25
critic-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-step-num: 5000000
action-dim: 12
actor-l2-reg: 0.0003
total-step-num: 2500000000
filter-action: True
gating-layer-size: [128, 128]
dsr-gait-freq: 1.667
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
filter-torque: False
dsr-gait-period: 0.6
bullet-default-PD: False
critic-layer-size: [256, 256]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
replay-ratio: 1
loss-output-diff-coeff: 0
Physics-frequency: 1000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-activation-fn: ['relu', 'relu', 'None']
squash-action: True
rollout-step-num: 1
loss-entropy-coeff: 0.0
actor-weight-decay: 1e-06
task-weight: 0.3
prioritized-exp-replay: True
max-test-time: 10
epoch-num: 500
critic-lr: 0.0003
train-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 8
LLC-frequency: 500
interpolation: False
batch-size: 128
critic-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
joint-interpolation: True
max-path-step: 5000
env-id: HumanoidBalanceFilter-v0
replay-start-size: 10000
tau: 0.001
max-episode-num: 5000000
critic-weight-decay: 1e-06
max-train-time: 10
replay-buffer-size: 1000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
HLC-frequency: 25
loss-output-smooth-coeff: 2.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
record-start-size: 10000.0
max-path-num: 20
n-step: 1
gating-activation-fn: ['relu', 'relu', 'None']
