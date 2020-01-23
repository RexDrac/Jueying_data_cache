normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
reward-scale: 0.1
prioritized-exp-replay: True
actor-layer-size: [256, 256]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-train-time: 10
test-num: 4
filter-action: True
tau: 0.001
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 2.0
bullet-default-PD: False
dsr-gait-period: 0.6
critic-weight-decay: 1e-06
replay-ratio: 1
LLC-frequency: 500
actor-lr: 0.0003
max-test-time: 10
record-start-size: 10000.0
state-dim: 25
squash-action: True
gating-layer-size: [128, 128]
gating-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
critic-layer-size: [256, 256]
max-path-num: 20
critic-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
task-weight: 0.2
total-step-num: 2500000000
actor-weight-decay: 1e-06
expert-num: 8
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
dsr-gait-freq: 1.667
loss-output-bound-coeff: 0.0
imitation-weight: 0.4
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
replay-start-size: 10000
critic-lr: 0.0003
joint-interpolation: True
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
render-eval: False
actor-l2-reg: 0.0003
critic-l2-reg: 0.0003
max-episode-num: 5000000
Physics-frequency: 1000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-path-step: 5000
actor-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
epoch-num: 500
loss-output-diff-coeff: 0
n-step: 1
loss-entropy-coeff: 0.0
goal-weight: 0.4
action-dim: 12
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-step-num: 2500000000
rollout-step-num: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
interpolation: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
epoch-step-num: 5000000
gamma: 0.986
filter-torque: False
