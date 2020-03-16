loss-entropy-coeff: 0.0
interpolation: False
actor-lr: 0.0003
train-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-bound-coeff: 0.0
reward-scale: 0.1
max-path-num: 20
critic-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
epoch-step-num: 5000000
max-test-time: 10
expert-num: 8
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
prioritized-exp-replay: True
max-step-num: 2500000000
tau: 0.001
dsr-gait-freq: 1.667
replay-ratio: 1
env-id: HumanoidBalanceFilter-v0
gating-layer-size: [128, 128]
batch-size: 128
max-path-step: 5000
test-num: 4
joint-interpolation: True
actor-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
rollout-step-num: 1
goal-weight: 0.4
dsr-gait-period: 0.6
squash-action: True
task-weight: 0.2
n-step: 1
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-train-time: 10
replay-start-size: 10000
imitation-weight: 0.4
loss-output-smooth-coeff: 2.0
critic-lr: 0.0003
total-step-num: 2500000000
record-start-size: 10000.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
actor-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-activation-fn: ['relu', 'relu', 'None']
state-dim: 25
gamma: 0.986
Physics-frequency: 1000
replay-buffer-size: 1000000
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
actor-layer-size: [256, 256]
critic-weight-decay: 1e-06
HLC-frequency: 25
render-eval: False
epoch-num: 500
actor-weight-decay: 1e-06
bullet-default-PD: False
loss-output-diff-coeff: 0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
gating-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
max-episode-num: 5000000
filter-action: True
