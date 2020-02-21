train-step-num: 1
gamma: 0.986
actor-l2-reg: 0.0003
prioritized-exp-replay: True
reward-scale: 0.1
max-path-step: 5000
state-dim: 25
imitation-weight: 0.4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
task-weight: 0.2
LLC-frequency: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
interpolation: False
max-train-time: 10
filter-torque: False
epoch-num: 500
actor-lr: 0.0003
critic-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
n-step: 1
dsr-gait-period: 0.6
replay-ratio: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
loss-output-smooth-coeff: 2.0
max-episode-num: 5000000
joint-interpolation: True
loss-output-bound-coeff: 0.0
test-num: 4
critic-l2-reg: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
gating-layer-size: [128, 128]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
Physics-frequency: 1000
rollout-step-num: 1
tau: 0.001
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
render-eval: False
replay-start-size: 10000
filter-action: True
loss-output-diff-coeff: 0
actor-weight-decay: 1e-06
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
epoch-step-num: 5000000
loss-entropy-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
total-step-num: 2500000000
actor-layer-size: [256, 256]
critic-weight-decay: 1e-06
critic-lr: 0.0003
squash-action: True
bullet-default-PD: False
max-step-num: 2500000000
goal-weight: 0.4
expert-num: 6
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
max-path-num: 20
replay-buffer-size: 1000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
dsr-gait-freq: 1.667
max-test-time: 10
