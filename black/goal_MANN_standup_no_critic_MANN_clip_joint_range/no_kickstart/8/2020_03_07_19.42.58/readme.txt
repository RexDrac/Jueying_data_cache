gating-layer-size: [128, 128]
total-step-num: 2500000000
joint-interpolation: True
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-l2-reg: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-bound-coeff: 0.0
gamma: 0.986
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
critic-layer-size: [256, 256]
test-num: 4
render-eval: False
filter-action: True
max-train-time: 10
train-step-num: 1
state-dim: 25
batch-size: 128
critic-lr: 0.0003
bullet-default-PD: False
actor-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
dsr-gait-freq: 1.667
n-step: 1
tau: 0.001
loss-output-diff-coeff: 0
HLC-frequency: 25
critic-weight-decay: 1e-06
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
max-path-num: 20
expert-num: 8
replay-ratio: 1
loss-entropy-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
epoch-num: 500
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-test-time: 10
actor-layer-size: [256, 256]
replay-buffer-size: 1000000
dsr-gait-period: 0.6
epoch-step-num: 5000000
critic-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-lr: 0.0003
max-path-step: 5000
imitation-weight: 0.4
max-step-num: 2500000000
LLC-frequency: 500
interpolation: False
prioritized-exp-replay: True
goal-weight: 0.4
gating-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-start-size: 10000
squash-action: True
filter-torque: False
Physics-frequency: 1000
task-weight: 0.2
rollout-step-num: 1
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
loss-output-smooth-coeff: 2.0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-weight-decay: 1e-06
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
