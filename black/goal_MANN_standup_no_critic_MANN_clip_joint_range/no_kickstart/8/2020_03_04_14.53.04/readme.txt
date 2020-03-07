batch-size: 128
actor-lr: 0.0003
max-train-time: 10
imitation-weight: 0.4
gating-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
gating-layer-size: [128, 128]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
total-step-num: 2500000000
Physics-frequency: 1000
epoch-num: 500
action-dim: 12
record-start-size: 10000.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-weight-decay: 1e-06
dsr-gait-period: 0.6
train-step-num: 1
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
n-step: 1
critic-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-episode-num: 5000000
replay-buffer-size: 1000000
epoch-step-num: 5000000
critic-weight-decay: 1e-06
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-output-diff-coeff: 0
replay-ratio: 1
squash-action: True
test-num: 4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
tau: 0.001
expert-num: 8
gamma: 0.986
bullet-default-PD: False
dsr-gait-freq: 1.667
actor-l2-reg: 0.0003
loss-entropy-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
filter-action: True
critic-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
render-eval: False
actor-layer-size: [256, 256]
HLC-frequency: 25
task-weight: 0.2
max-test-time: 10
critic-layer-size: [256, 256]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-path-step: 5000
reward-scale: 0.1
max-step-num: 2500000000
state-dim: 25
max-path-num: 20
filter-torque: False
goal-weight: 0.4
actor-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
loss-output-smooth-coeff: 2.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
joint-interpolation: True
interpolation: False
prioritized-exp-replay: True
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
