LLC-frequency: 500
rollout-step-num: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
gamma: 0.986
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
gating-layer-size: [128, 128]
imitation-weight: 0.4
joint-interpolation: True
batch-size: 128
replay-buffer-size: 1000000
max-path-num: 20
loss-output-bound-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
replay-ratio: 1
actor-lr: 0.0003
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
actor-layer-size: [256, 256]
epoch-step-num: 5000000
Physics-frequency: 1000
critic-layer-size: [256, 256]
max-episode-num: 5000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-weight-decay: 1e-06
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
goal-weight: 0.4
gating-activation-fn: ['relu', 'relu', 'None']
n-step: 1
critic-l2-reg: 0.0003
total-step-num: 2500000000
squash-action: True
critic-activation-fn: ['relu', 'relu', 'None']
dsr-gait-freq: 1.667
action-dim: 12
loss-entropy-coeff: 0.0
expert-num: 8
record-start-size: 10000.0
prioritized-exp-replay: True
max-path-step: 5000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
filter-torque: False
max-train-time: 10
critic-lr: 0.0003
interpolation: False
test-num: 4
render-eval: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
loss-output-smooth-coeff: 2.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-test-time: 10
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
critic-weight-decay: 1e-06
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
dsr-gait-period: 0.6
train-step-num: 1
state-dim: 25
reward-scale: 0.1
actor-l2-reg: 0.0003
HLC-frequency: 25
loss-output-diff-coeff: 0
epoch-num: 500
task-weight: 0.2
max-step-num: 2500000000
