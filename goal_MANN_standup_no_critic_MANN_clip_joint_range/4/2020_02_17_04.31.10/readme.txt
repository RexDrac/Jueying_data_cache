gating-mask: [[1.0, 1.0, 1.0, 1.0]]
epoch-step-num: 5000000
replay-ratio: 1
n-step: 1
max-step-num: 2500000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
tau: 0.001
epoch-num: 500
loss-output-diff-coeff: 0
filter-torque: False
goal-weight: 0.4
actor-layer-size: [256, 256]
dsr-gait-period: 0.6
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
test-num: 4
joint-interpolation: True
batch-size: 128
critic-weight-decay: 1e-06
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
reward-scale: 0.1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-smooth-coeff: 2.0
squash-action: True
loss-output-bound-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
actor-l2-reg: 0.0003
loss-entropy-coeff: 0.0
bullet-default-PD: False
render-eval: False
max-path-step: 5000
max-test-time: 10
critic-layer-size: [256, 256]
actor-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.2
action-dim: 12
state-dim: 25
train-step-num: 1
actor-weight-decay: 1e-06
replay-buffer-size: 1000000
critic-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
prioritized-exp-replay: True
replay-start-size: 10000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
HLC-frequency: 25
LLC-frequency: 500
Physics-frequency: 1000
total-step-num: 2500000000
filter-action: True
max-episode-num: 5000000
gamma: 0.986
max-path-num: 20
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
max-train-time: 10
interpolation: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-freq: 1.667
rollout-step-num: 1
gating-layer-size: [128, 128]
record-start-size: 10000.0
expert-num: 4
critic-l2-reg: 0.0003
imitation-weight: 0.4
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-lr: 0.0003
actor-lr: 0.0003
