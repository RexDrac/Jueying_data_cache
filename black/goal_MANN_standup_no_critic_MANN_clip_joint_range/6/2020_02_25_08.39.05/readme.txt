actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
loss-entropy-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
replay-buffer-size: 1000000
squash-action: True
actor-lr: 0.0003
prioritized-exp-replay: True
expert-num: 6
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
max-train-time: 10
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
bullet-default-PD: False
critic-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 0.4
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
goal-weight: 0.4
filter-action: True
n-step: 1
Physics-frequency: 1000
train-step-num: 1
actor-layer-size: [256, 256]
LLC-frequency: 500
actor-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [128, 128]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-path-num: 20
replay-start-size: 10000
critic-layer-size: [256, 256]
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
dsr-gait-freq: 1.667
state-dim: 25
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-step: 5000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-episode-num: 5000000
max-test-time: 10
actor-l2-reg: 0.0003
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
HLC-frequency: 25
reward-scale: 0.1
gamma: 0.986
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
loss-output-diff-coeff: 0
replay-ratio: 1
rollout-step-num: 1
test-num: 4
critic-weight-decay: 1e-06
total-step-num: 2500000000
record-start-size: 10000.0
loss-output-smooth-coeff: 2.0
epoch-num: 500
task-weight: 0.2
critic-lr: 0.0003
filter-torque: False
dsr-gait-period: 0.6
tau: 0.001
critic-l2-reg: 0.0003
action-dim: 12
epoch-step-num: 5000000
batch-size: 128
render-eval: False
loss-output-bound-coeff: 0.0
