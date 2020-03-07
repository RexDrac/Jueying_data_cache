batch-size: 128
gamma: 0.986
rollout-step-num: 1
HLC-frequency: 25
dsr-gait-freq: 1.667
critic-weight-decay: 1e-06
prioritized-exp-replay: True
epoch-step-num: 5000000
imitation-weight: 0.4
n-step: 1
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-test-time: 10
actor-layer-size: [256, 256]
joint-interpolation: True
epoch-num: 500
gating-layer-size: [128, 128]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-torque: False
loss-output-bound-coeff: 0.0
loss-output-smooth-coeff: 2.0
max-train-time: 10
actor-weight-decay: 1e-06
reward-scale: 0.1
max-episode-num: 5000000
LLC-frequency: 500
gating-activation-fn: ['relu', 'relu', 'None']
goal-weight: 0.4
action-dim: 12
replay-buffer-size: 1000000
max-path-step: 5000
replay-ratio: 1
actor-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
replay-start-size: 10000
interpolation: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
bullet-default-PD: False
max-path-num: 20
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-step-num: 2500000000
record-start-size: 10000.0
filter-action: True
tau: 0.001
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
expert-num: 8
actor-l2-reg: 0.0003
task-weight: 0.2
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
env-id: HumanoidBalanceFilter-v0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 25
actor-lr: 0.0003
render-eval: False
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
dsr-gait-period: 0.6
critic-layer-size: [256, 256]
Physics-frequency: 1000
total-step-num: 2500000000
critic-l2-reg: 0.0003
loss-entropy-coeff: 0.0
test-num: 4
squash-action: True
