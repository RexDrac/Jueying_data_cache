actor-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
actor-weight-decay: 1e-06
epoch-step-num: 5000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
dsr-gait-period: 0.6
actor-l2-reg: 0.0003
max-path-step: 5000
Physics-frequency: 1000
critic-weight-decay: 1e-06
critic-l2-reg: 0.0003
prioritized-exp-replay: True
dsr-gait-freq: 1.667
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-entropy-coeff: 0.0
actor-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
batch-size: 128
interpolation: False
loss-output-bound-coeff: 0.0
critic-lr: 0.0003
reward-scale: 0.1
critic-activation-fn: ['relu', 'relu', 'None']
critic-layer-size: [256, 256]
gamma: 0.986
action-dim: 12
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
epoch-num: 500
filter-action: True
joint-interpolation: True
loss-output-smooth-coeff: 2.0
env-id: HumanoidBalanceFilter-v0
imitation-weight: 0.4
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
test-num: 4
squash-action: True
loss-output-diff-coeff: 0
LLC-frequency: 500
bullet-default-PD: False
state-dim: 25
max-episode-num: 5000000
max-train-time: 10
record-start-size: 10000.0
gating-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
rollout-step-num: 1
total-step-num: 2500000000
n-step: 1
replay-start-size: 10000
expert-num: 8
render-eval: False
goal-weight: 0.4
gating-layer-size: [128, 128]
task-weight: 0.2
tau: 0.001
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
filter-torque: False
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
HLC-frequency: 25
max-path-num: 20
replay-ratio: 1
max-step-num: 2500000000
max-test-time: 10
