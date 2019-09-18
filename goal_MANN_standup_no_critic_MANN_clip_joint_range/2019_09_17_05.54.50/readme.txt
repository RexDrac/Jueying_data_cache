state-dim: 25
rollout-step-num: 1
action-dim: 12
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
HLC-frequency: 25
dsr-gait-period: 0.6
gating-layer-size: [128, 128]
max-step-num: 2500000000
env-id: HumanoidBalanceFilter-v0
critic-lr: 0.0003
loss-output-bound-coeff: 0.0
prioritized-exp-replay: True
epoch-num: 500
gating-activation-fn: ['relu', 'relu', 'None']
squash-action: True
dsr-gait-freq: 1.667
loss-output-diff-coeff: 0
loss-output-smooth-coeff: 2.0
replay-start-size: 10000
critic-weight-decay: 1e-06
LLC-frequency: 500
critic-activation-fn: ['relu', 'relu', 'None']
filter-action: True
tau: 0.001
test-num: 4
max-test-time: 10
max-train-time: 10
expert-num: 8
max-path-step: 5000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
render-eval: False
batch-size: 128
n-step: 1
epoch-step-num: 5000000
actor-weight-decay: 1e-06
bullet-default-PD: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
record-start-size: 10000.0
replay-buffer-size: 1000000
gamma: 0.986
actor-lr: 0.0003
total-step-num: 2500000000
critic-l2-reg: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
filter-torque: False
critic-layer-size: [256, 256]
actor-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
train-step-num: 1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-l2-reg: 0.0003
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
imitation-weight: 0.5
interpolation: False
reward-scale: 0.1
max-episode-num: 5000000
loss-entropy-coeff: 0.0
replay-ratio: 1
task-weight: 0.5
max-path-num: 20
actor-layer-size: [256, 256]
joint-interpolation: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
