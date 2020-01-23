replay-ratio: 1
critic-lr: 0.0003
actor-layer-size: [256, 256]
loss-entropy-coeff: 0.0
epoch-step-num: 5000000
n-step: 1
test-num: 4
rollout-step-num: 1
prioritized-exp-replay: True
imitation-weight: 0.4
actor-weight-decay: 1e-06
dsr-gait-period: 0.6
task-weight: 0.2
batch-size: 128
env-id: HumanoidBalanceFilter-v0
expert-num: 8
reward-scale: 0.1
replay-start-size: 10000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
train-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
Physics-frequency: 1000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-episode-num: 5000000
critic-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
max-path-step: 5000
max-train-time: 10
loss-output-diff-coeff: 0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-l2-reg: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
critic-weight-decay: 1e-06
loss-output-bound-coeff: 0.0
state-dim: 25
record-start-size: 10000.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-test-time: 10
squash-action: True
goal-weight: 0.4
replay-buffer-size: 1000000
max-step-num: 2500000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
filter-torque: False
total-step-num: 2500000000
actor-l2-reg: 0.0003
HLC-frequency: 25
dsr-gait-freq: 1.667
epoch-num: 500
loss-output-smooth-coeff: 2.0
action-dim: 12
LLC-frequency: 500
max-path-num: 20
critic-layer-size: [256, 256]
filter-action: True
interpolation: False
gating-activation-fn: ['relu', 'relu', 'None']
tau: 0.001
joint-interpolation: True
gating-layer-size: [128, 128]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
render-eval: False
gamma: 0.986
