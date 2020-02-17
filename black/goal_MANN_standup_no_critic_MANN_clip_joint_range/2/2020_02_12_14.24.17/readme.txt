interpolation: False
actor-lr: 0.0003
LLC-frequency: 500
filter-action: True
total-step-num: 2500000000
max-path-step: 5000
dsr-gait-freq: 1.667
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
render-eval: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
max-train-time: 10
n-step: 1
loss-output-diff-coeff: 0
loss-entropy-coeff: 0.0
test-num: 4
tau: 0.001
actor-l2-reg: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
dsr-gait-period: 0.6
critic-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
squash-action: True
prioritized-exp-replay: True
epoch-step-num: 5000000
HLC-frequency: 25
imitation-weight: 0.4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
goal-weight: 0.4
joint-interpolation: True
loss-output-smooth-coeff: 2.0
bullet-default-PD: False
batch-size: 128
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-layer-size: [128, 128]
Physics-frequency: 1000
critic-lr: 0.0003
max-episode-num: 5000000
max-path-num: 20
max-step-num: 2500000000
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
reward-scale: 0.1
loss-output-bound-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
replay-start-size: 10000
actor-weight-decay: 1e-06
state-dim: 25
actor-layer-size: [256, 256]
critic-weight-decay: 1e-06
task-weight: 0.2
gating-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
expert-num: 2
gating-mask: [[1.0, 1.0]]
env-id: HumanoidBalanceFilter-v0
critic-l2-reg: 0.0003
critic-layer-size: [256, 256]
replay-buffer-size: 1000000
train-step-num: 1
filter-torque: False
replay-ratio: 1
epoch-num: 500
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
rollout-step-num: 1
max-test-time: 10
gamma: 0.986
