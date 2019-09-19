task-weight: 0.5
imitation-weight: 0.5
actor-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
critic-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
max-path-step: 5000
replay-ratio: 1
replay-buffer-size: 1000000
reward-scale: 0.1
actor-weight-decay: 1e-06
squash-action: True
actor-lr: 0.0003
max-episode-num: 5000000
tau: 0.001
max-step-num: 2500000000
joint-interpolation: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
loss-entropy-coeff: 0.0
train-step-num: 1
prioritized-exp-replay: True
n-step: 1
HLC-frequency: 25
test-num: 4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-lr: 0.0003
loss-output-diff-coeff: 0
filter-action: True
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
expert-num: 8
render-eval: False
loss-output-smooth-coeff: 1.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
loss-output-bound-coeff: 0.0
dsr-gait-freq: 1.667
action-dim: 12
gamma: 0.986
LLC-frequency: 500
actor-layer-size: [256, 256]
actor-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
batch-size: 128
replay-start-size: 10000
critic-layer-size: [256, 256]
total-step-num: 2500000000
epoch-num: 500
gating-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
env-id: HumanoidBalanceFilter-v0
rollout-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
state-dim: 25
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-layer-size: [128, 128]
critic-weight-decay: 1e-06
Physics-frequency: 1000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
critic-l2-reg: 0.0003
epoch-step-num: 5000000
filter-torque: False
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
max-test-time: 10
