tau: 0.001
joint-interpolation: True
loss-entropy-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
rollout-step-num: 1
actor-l2-reg: 0.0003
replay-buffer-size: 1000000
squash-action: True
filter-torque: False
critic-lr: 0.0003
test-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
expert-num: 8
dsr-gait-period: 0.6
actor-activation-fn: ['relu', 'relu', 'None']
max-path-step: 5000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-path-num: 20
actor-weight-decay: 1e-06
imitation-weight: 0.5
actor-layer-size: [256, 256]
max-step-num: 2500000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
prioritized-exp-replay: True
bullet-default-PD: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
gating-layer-size: [128, 128]
critic-weight-decay: 1e-06
critic-layer-size: [256, 256]
max-train-time: 10
Physics-frequency: 1000
total-step-num: 2500000000
max-episode-num: 5000000
render-eval: False
replay-start-size: 10000
task-weight: 0.5
epoch-num: 500
n-step: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
filter-action: True
max-test-time: 10
env-id: HumanoidBalanceFilter-v0
record-start-size: 10000.0
HLC-frequency: 25
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-diff-coeff: 0
replay-ratio: 1
critic-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
gamma: 0.955
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-l2-reg: 0.0003
train-step-num: 1
actor-lr: 0.0003
loss-output-smooth-coeff: 1.0
loss-output-bound-coeff: 0.0
epoch-step-num: 5000000
action-dim: 12
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
state-dim: 25
batch-size: 128
dsr-gait-freq: 1.667
interpolation: False
