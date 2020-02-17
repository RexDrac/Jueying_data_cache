train-step-num: 1
gating-layer-size: [128, 128]
critic-lr: 0.0003
max-test-time: 10
n-step: 1
replay-ratio: 1
dsr-gait-period: 0.6
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
loss-entropy-coeff: 0.0
dsr-gait-freq: 1.667
critic-layer-size: [256, 256]
filter-torque: False
total-step-num: 2500000000
epoch-num: 500
HLC-frequency: 25
actor-layer-size: [256, 256]
critic-weight-decay: 1e-06
actor-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.5
max-train-time: 10
Physics-frequency: 1000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-diff-coeff: 0
reward-scale: 0.1
epoch-step-num: 5000000
prioritized-exp-replay: True
replay-start-size: 10000
actor-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
squash-action: True
max-path-step: 5000
actor-lr: 0.0003
interpolation: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
state-dim: 25
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
imitation-weight: 0.5
max-step-num: 2500000000
LLC-frequency: 500
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
max-episode-num: 5000000
loss-output-smooth-coeff: 3.0
gamma: 0.986
filter-action: True
action-dim: 12
batch-size: 128
bullet-default-PD: False
tau: 0.001
expert-num: 8
loss-output-bound-coeff: 0.0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
rollout-step-num: 1
replay-buffer-size: 1000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-activation-fn: ['relu', 'relu', 'None']
render-eval: False
actor-weight-decay: 1e-06
test-num: 4
env-id: HumanoidBalanceFilter-v0
joint-interpolation: True
