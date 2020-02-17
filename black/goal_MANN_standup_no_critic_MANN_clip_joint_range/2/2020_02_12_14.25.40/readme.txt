prioritized-exp-replay: True
HLC-frequency: 25
actor-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
max-test-time: 10
loss-entropy-coeff: 0.0
squash-action: True
LLC-frequency: 500
critic-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
n-step: 1
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
goal-weight: 0.4
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
reward-scale: 0.1
gamma: 0.986
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-lr: 0.0003
epoch-num: 500
record-start-size: 10000.0
bullet-default-PD: False
replay-start-size: 10000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
env-id: HumanoidBalanceFilter-v0
action-dim: 12
task-weight: 0.2
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
train-step-num: 1
filter-action: True
replay-ratio: 1
test-num: 4
max-episode-num: 5000000
critic-l2-reg: 0.0003
max-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
total-step-num: 2500000000
loss-output-bound-coeff: 0.0
gating-layer-size: [128, 128]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-diff-coeff: 0
tau: 0.001
actor-activation-fn: ['relu', 'relu', 'None']
state-dim: 25
max-path-step: 5000
gating-mask: [[1.0, 1.0]]
interpolation: False
epoch-step-num: 5000000
critic-lr: 0.0003
render-eval: False
batch-size: 128
critic-weight-decay: 1e-06
expert-num: 2
imitation-weight: 0.4
actor-l2-reg: 0.0003
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
Physics-frequency: 1000
joint-interpolation: True
max-path-num: 20
actor-weight-decay: 1e-06
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-smooth-coeff: 2.0
replay-buffer-size: 1000000
filter-torque: False
dsr-gait-freq: 1.667
critic-layer-size: [256, 256]
max-train-time: 10
rollout-step-num: 1
