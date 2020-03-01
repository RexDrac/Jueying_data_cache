critic-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [128, 128]
record-start-size: 10000.0
max-test-time: 10
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
prioritized-exp-replay: True
max-episode-num: 5000000
actor-layer-size: [256, 256]
loss-entropy-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
env-id: HumanoidBalanceFilter-v0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
train-step-num: 1
max-train-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
rollout-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
max-path-num: 20
actor-lr: 0.0003
filter-action: True
actor-l2-reg: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
loss-output-bound-coeff: 0.0
critic-l2-reg: 0.0003
batch-size: 128
interpolation: False
loss-output-smooth-coeff: 2.0
replay-start-size: 10000
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
gamma: 0.986
dsr-gait-period: 0.6
goal-weight: 0.4
reward-scale: 0.1
n-step: 1
render-eval: False
max-step-num: 2500000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
joint-interpolation: True
bullet-default-PD: False
task-weight: 0.2
replay-ratio: 1
max-path-step: 5000
critic-layer-size: [256, 256]
test-num: 4
total-step-num: 2500000000
expert-num: 8
tau: 0.001
epoch-num: 500
critic-weight-decay: 1e-06
actor-weight-decay: 1e-06
critic-lr: 0.0003
Physics-frequency: 1000
filter-torque: False
LLC-frequency: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
squash-action: True
epoch-step-num: 5000000
dsr-gait-freq: 1.667
loss-output-diff-coeff: 0
state-dim: 25
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
imitation-weight: 0.4
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
