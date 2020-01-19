state-dim: 25
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-weight-decay: 1e-06
max-path-step: 5000
n-step: 1
test-num: 4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-test-time: 10
train-step-num: 1
tau: 0.001
HLC-frequency: 25
record-start-size: 10000.0
actor-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
imitation-weight: 0.5
critic-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-start-size: 10000
dsr-gait-period: 0.6
critic-lr: 0.0003
reward-scale: 0.1
epoch-step-num: 5000000
max-step-num: 2500000000
prioritized-exp-replay: True
loss-output-smooth-coeff: 1.0
Physics-frequency: 1000
interpolation: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
render-eval: False
max-train-time: 10
max-episode-num: 5000000
action-dim: 12
critic-weight-decay: 1e-06
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
filter-torque: False
gating-layer-size: [128, 128]
expert-num: 8
loss-output-bound-coeff: 0.0
loss-output-diff-coeff: 0
gating-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
replay-ratio: 1
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-layer-size: [256, 256]
bullet-default-PD: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
squash-action: True
rollout-step-num: 1
replay-buffer-size: 1000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
epoch-num: 500
joint-interpolation: True
task-weight: 0.5
actor-lr: 0.0003
critic-l2-reg: 0.0003
dsr-gait-freq: 1.667
filter-action: True
actor-activation-fn: ['relu', 'relu', 'None']
critic-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
env-id: HumanoidBalanceFilter-v0
LLC-frequency: 500
gamma: 0.986
batch-size: 128
max-path-num: 20
