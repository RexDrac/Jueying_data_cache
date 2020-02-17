HLC-frequency: 25
action-dim: 12
max-path-num: 20
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
state-dim: 25
gating-layer-size: [128, 128]
critic-lr: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-episode-num: 5000000
epoch-num: 500
actor-layer-size: [256, 256]
dsr-gait-freq: 1.667
reward-scale: 0.1
gamma: 0.955
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
loss-output-diff-coeff: 0
max-path-step: 5000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
render-eval: False
dsr-gait-period: 0.6
loss-entropy-coeff: 0.0
n-step: 1
actor-lr: 0.0003
replay-buffer-size: 1000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-output-bound-coeff: 0.0
record-start-size: 10000.0
squash-action: True
Physics-frequency: 1000
actor-weight-decay: 1e-06
epoch-step-num: 5000000
prioritized-exp-replay: True
env-id: HumanoidBalanceFilter-v0
max-step-num: 2500000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
train-step-num: 1
critic-weight-decay: 1e-06
max-test-time: 10
expert-num: 4
LLC-frequency: 500
filter-torque: False
max-train-time: 10
actor-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 0.5
critic-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
test-num: 4
tau: 0.001
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
loss-output-smooth-coeff: 1.0
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
task-weight: 0.5
critic-l2-reg: 0.0003
actor-l2-reg: 0.0003
total-step-num: 2500000000
rollout-step-num: 1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
joint-interpolation: True
interpolation: False
