total-step-num: 2500000000
replay-buffer-size: 1000000
actor-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
dsr-gait-period: 0.6
max-train-time: 10
reward-scale: 0.1
action-dim: 12
record-start-size: 10000.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
HLC-frequency: 25
train-step-num: 1
bullet-default-PD: False
imitation-weight: 0.5
actor-lr: 0.0003
max-step-num: 2500000000
critic-l2-reg: 0.0003
interpolation: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-ratio: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
expert-num: 4
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
loss-output-smooth-coeff: 1.0
gating-layer-size: [128, 128]
actor-layer-size: [256, 256]
state-dim: 25
max-test-time: 10
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-torque: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
rollout-step-num: 1
loss-output-diff-coeff: 0
critic-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-episode-num: 5000000
test-num: 4
task-weight: 0.5
epoch-step-num: 5000000
max-path-step: 5000
joint-interpolation: True
gamma: 0.955
critic-lr: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-entropy-coeff: 0.0
render-eval: False
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
batch-size: 128
critic-layer-size: [256, 256]
replay-start-size: 10000
Physics-frequency: 1000
max-path-num: 20
tau: 0.001
filter-action: True
loss-output-bound-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
n-step: 1
env-id: HumanoidBalanceFilter-v0
critic-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
dsr-gait-freq: 1.667
squash-action: True
