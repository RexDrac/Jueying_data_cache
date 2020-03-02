critic-layer-size: [256, 256]
loss-output-diff-coeff: 0
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
critic-lr: 0.0003
dsr-gait-period: 0.6
imitation-weight: 0.4
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
record-start-size: 10000.0
expert-num: 8
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-freq: 1.667
max-test-time: 10
filter-torque: False
env-id: HumanoidBalanceFilter-v0
filter-action: True
critic-weight-decay: 1e-06
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-ratio: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-num: 500
actor-weight-decay: 1e-06
rollout-step-num: 1
goal-weight: 0.4
state-dim: 25
loss-entropy-coeff: 0.0
n-step: 1
LLC-frequency: 500
task-weight: 0.2
gating-activation-fn: ['relu', 'relu', 'None']
test-num: 4
max-train-time: 10
actor-lr: 0.0003
gamma: 0.986
critic-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
loss-output-bound-coeff: 0.0
render-eval: False
Physics-frequency: 1000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
joint-interpolation: True
actor-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
loss-output-smooth-coeff: 2.0
replay-buffer-size: 1000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-step-num: 2500000000
interpolation: False
gating-layer-size: [128, 128]
tau: 0.001
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
bullet-default-PD: False
max-episode-num: 5000000
prioritized-exp-replay: True
max-path-num: 20
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-l2-reg: 0.0003
total-step-num: 2500000000
HLC-frequency: 25
epoch-step-num: 5000000
action-dim: 12
squash-action: True
reward-scale: 0.1
actor-l2-reg: 0.0003
actor-layer-size: [256, 256]
