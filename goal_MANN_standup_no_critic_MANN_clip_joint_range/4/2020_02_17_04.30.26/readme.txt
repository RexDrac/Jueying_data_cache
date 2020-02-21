gating-mask: [[1.0, 1.0, 1.0, 1.0]]
tau: 0.001
goal-weight: 0.4
imitation-weight: 0.4
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
epoch-num: 500
critic-l2-reg: 0.0003
n-step: 1
LLC-frequency: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-action: True
actor-lr: 0.0003
dsr-gait-period: 0.6
render-eval: False
rollout-step-num: 1
max-test-time: 10
epoch-step-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-lr: 0.0003
squash-action: True
action-dim: 12
replay-start-size: 10000
total-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
test-num: 4
reward-scale: 0.1
max-episode-num: 5000000
critic-weight-decay: 1e-06
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
expert-num: 4
Physics-frequency: 1000
interpolation: False
actor-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
record-start-size: 10000.0
critic-layer-size: [256, 256]
max-path-num: 20
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
replay-ratio: 1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
state-dim: 25
critic-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
dsr-gait-freq: 1.667
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-entropy-coeff: 0.0
bullet-default-PD: False
joint-interpolation: True
prioritized-exp-replay: True
max-path-step: 5000
batch-size: 128
task-weight: 0.2
gating-layer-size: [128, 128]
HLC-frequency: 25
filter-torque: False
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
env-id: HumanoidBalanceFilter-v0
gamma: 0.986
actor-weight-decay: 1e-06
loss-output-bound-coeff: 0.0
actor-layer-size: [256, 256]
loss-output-diff-coeff: 0
train-step-num: 1
actor-l2-reg: 0.0003
loss-output-smooth-coeff: 2.0
