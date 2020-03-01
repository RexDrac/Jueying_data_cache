dsr-gait-period: 0.6
loss-entropy-coeff: 0.0
max-path-step: 5000
epoch-step-num: 5000000
record-start-size: 10000.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.2
epoch-num: 500
render-eval: False
tau: 0.001
loss-output-smooth-coeff: 2.0
train-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
reward-scale: 0.1
max-path-num: 20
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
actor-layer-size: [256, 256]
critic-layer-size: [256, 256]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-buffer-size: 1000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
Physics-frequency: 1000
actor-weight-decay: 1e-06
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
loss-output-diff-coeff: 0
critic-lr: 0.0003
joint-interpolation: True
env-id: HumanoidBalanceFilter-v0
max-episode-num: 5000000
LLC-frequency: 500
test-num: 4
max-test-time: 10
action-dim: 12
prioritized-exp-replay: True
filter-torque: False
replay-ratio: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
actor-l2-reg: 0.0003
gamma: 0.986
HLC-frequency: 25
squash-action: True
bullet-default-PD: False
filter-action: True
goal-weight: 0.4
loss-output-bound-coeff: 0.0
expert-num: 8
critic-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-weight-decay: 1e-06
replay-start-size: 10000
interpolation: False
gating-layer-size: [128, 128]
max-train-time: 10
critic-l2-reg: 0.0003
rollout-step-num: 1
actor-lr: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
state-dim: 25
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-freq: 1.667
imitation-weight: 0.4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
