actor-l2-reg: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
total-step-num: 2500000000
replay-buffer-size: 1000000
HLC-frequency: 25
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-ratio: 1
bullet-default-PD: False
loss-output-bound-coeff: 0.0
prioritized-exp-replay: True
gating-layer-size: [128, 128]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-output-smooth-coeff: 1.0
rollout-step-num: 1
imitation-weight: 0.5
dsr-gait-period: 0.6
batch-size: 128
epoch-num: 500
max-train-time: 10
env-id: HumanoidBalanceFilter-v0
LLC-frequency: 500
gating-activation-fn: ['relu', 'relu', 'None']
gamma: 0.955
critic-l2-reg: 0.0003
max-test-time: 10
max-episode-num: 5000000
actor-weight-decay: 1e-06
tau: 0.001
task-weight: 0.5
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
test-num: 4
actor-activation-fn: ['relu', 'relu', 'None']
dsr-gait-freq: 1.667
epoch-step-num: 5000000
Physics-frequency: 1000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
filter-torque: False
loss-entropy-coeff: 0.0
interpolation: False
state-dim: 25
max-step-num: 2500000000
reward-scale: 0.1
expert-num: 4
n-step: 1
max-path-step: 5000
record-start-size: 10000.0
render-eval: False
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
train-step-num: 1
max-path-num: 20
joint-interpolation: True
replay-start-size: 10000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-action: True
critic-weight-decay: 1e-06
critic-activation-fn: ['relu', 'relu', 'None']
critic-layer-size: [256, 256]
loss-output-diff-coeff: 0
actor-layer-size: [256, 256]
actor-lr: 0.0003
squash-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-lr: 0.0003
