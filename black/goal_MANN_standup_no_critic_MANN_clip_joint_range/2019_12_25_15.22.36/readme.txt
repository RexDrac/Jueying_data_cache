dsr-gait-period: 0.6
critic-l2-reg: 0.0003
actor-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-bound-coeff: 0.0
max-train-time: 10
critic-layer-size: [256, 256]
record-start-size: 10000.0
loss-entropy-coeff: 0.0
replay-ratio: 1
bullet-default-PD: False
rollout-step-num: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-freq: 1.667
env-id: HumanoidBalanceFilter-v0
epoch-step-num: 5000000
gamma: 0.986
epoch-num: 500
filter-torque: False
loss-output-diff-coeff: 0
actor-activation-fn: ['relu', 'relu', 'None']
render-eval: False
expert-num: 8
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
filter-action: True
max-episode-num: 5000000
gating-layer-size: [128, 128]
interpolation: False
critic-weight-decay: 1e-06
actor-lr: 0.0003
Physics-frequency: 1000
LLC-frequency: 500
squash-action: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
actor-layer-size: [256, 256]
tau: 0.001
train-step-num: 1
max-path-num: 20
task-weight: 0.2
max-step-num: 2500000000
test-num: 4
n-step: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
joint-interpolation: True
goal-weight: 0.4
state-dim: 25
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-path-step: 5000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
imitation-weight: 0.4
loss-output-smooth-coeff: 2.0
critic-lr: 0.0003
replay-buffer-size: 1000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-l2-reg: 0.0003
prioritized-exp-replay: True
total-step-num: 2500000000
max-test-time: 10
action-dim: 12
replay-start-size: 10000
reward-scale: 0.1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
