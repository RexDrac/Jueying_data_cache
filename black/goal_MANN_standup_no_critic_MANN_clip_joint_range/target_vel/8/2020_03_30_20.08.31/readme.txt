max-path-num: 20
n-step: 1
squash-action: True
Physics-frequency: 1000
prioritized-exp-replay: True
max-path-step: 5000
actor-weight-decay: 1e-06
actor-l2-reg: 0.0003
actor-lr: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
replay-buffer-size: 1000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
reward-scale: 0.1
interpolation: False
gamma: 0.986
test-num: 4
dsr-gait-freq: 1.667
task-weight: 0.2
action-dim: 12
max-step-num: 2500000000
gating-layer-size: [128, 128]
joint-interpolation: True
dsr-gait-period: 0.6
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-layer-size: [256, 256]
critic-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-ratio: 1
tau: 0.001
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
rollout-step-num: 1
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
critic-lr: 0.0003
loss-output-bound-coeff: 0.0
epoch-num: 500
critic-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
imitation-weight: 0.4
batch-size: 128
loss-output-smooth-coeff: 2.0
HLC-frequency: 25
max-test-time: 10
LLC-frequency: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 25
loss-entropy-coeff: 0.0
filter-torque: False
env-id: HumanoidBalanceFilter-v0
goal-weight: 0.4
critic-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
filter-action: True
expert-num: 8
critic-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
render-eval: False
loss-output-diff-coeff: 0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-episode-num: 5000000
total-step-num: 2500000000
train-step-num: 1
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
epoch-step-num: 5000000
record-start-size: 10000.0
replay-start-size: 10000
