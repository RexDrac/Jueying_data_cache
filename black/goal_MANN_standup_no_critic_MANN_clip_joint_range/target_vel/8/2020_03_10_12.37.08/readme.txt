loss-entropy-coeff: 0.0
filter-torque: False
batch-size: 128
replay-ratio: 1
max-path-step: 5000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-layer-size: [128, 128]
filter-action: True
critic-activation-fn: ['relu', 'relu', 'None']
gamma: 0.986
prioritized-exp-replay: True
n-step: 1
epoch-step-num: 5000000
critic-weight-decay: 1e-06
critic-l2-reg: 0.0003
render-eval: False
actor-layer-size: [256, 256]
loss-output-bound-coeff: 0.0
bullet-default-PD: False
env-id: HumanoidBalanceFilter-v0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
LLC-frequency: 500
action-dim: 12
loss-output-diff-coeff: 0
train-step-num: 1
test-num: 4
total-step-num: 2500000000
replay-start-size: 10000
epoch-num: 500
gating-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
critic-layer-size: [256, 256]
critic-lr: 0.0003
task-weight: 0.2
tau: 0.001
actor-weight-decay: 1e-06
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
rollout-step-num: 1
interpolation: False
imitation-weight: 0.4
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
max-path-num: 20
dsr-gait-period: 0.6
expert-num: 8
actor-activation-fn: ['relu', 'relu', 'None']
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
squash-action: True
max-train-time: 10
reward-scale: 0.1
joint-interpolation: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
dsr-gait-freq: 1.667
max-episode-num: 5000000
state-dim: 25
max-step-num: 2500000000
HLC-frequency: 25
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-test-time: 10
loss-output-smooth-coeff: 2.0
actor-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
goal-weight: 0.4
Physics-frequency: 1000
record-start-size: 10000.0
