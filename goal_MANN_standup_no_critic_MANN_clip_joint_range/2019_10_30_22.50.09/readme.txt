action-dim: 12
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
reward-scale: 0.1
total-step-num: 2500000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
train-step-num: 1
max-path-step: 5000
HLC-frequency: 25
actor-layer-size: [256, 256]
Physics-frequency: 1000
gating-layer-size: [128, 128]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
LLC-frequency: 500
batch-size: 128
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
state-dim: 25
max-step-num: 2500000000
imitation-weight: 0.5
max-test-time: 10
dsr-gait-freq: 1.667
render-eval: False
rollout-step-num: 1
goal-weight: 0.5
loss-output-diff-coeff: 0
gamma: 0.986
n-step: 1
critic-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
critic-l2-reg: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
bullet-default-PD: False
interpolation: False
epoch-num: 500
joint-interpolation: True
squash-action: True
loss-output-bound-coeff: 0.0
record-start-size: 10000.0
replay-start-size: 10000
expert-num: 8
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-entropy-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-period: 0.6
epoch-step-num: 5000000
loss-output-smooth-coeff: 2.0
max-episode-num: 5000000
replay-buffer-size: 1000000
critic-weight-decay: 1e-06
env-id: HumanoidBalanceFilter-v0
task-weight: 0.0
prioritized-exp-replay: True
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-lr: 0.0003
tau: 0.001
max-path-num: 20
replay-ratio: 1
test-num: 4
max-train-time: 10
actor-weight-decay: 1e-06
filter-action: True
