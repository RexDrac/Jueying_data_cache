max-episode-num: 5000000
rollout-step-num: 1
max-path-step: 5000
test-num: 4
expert-num: 2
replay-buffer-size: 1000000
Physics-frequency: 1000
dsr-gait-period: 0.6
max-train-time: 10
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-weight-decay: 1e-06
critic-weight-decay: 1e-06
batch-size: 128
max-step-num: 2500000000
gating-layer-size: [128, 128]
critic-l2-reg: 0.0003
replay-ratio: 1
critic-lr: 0.0003
filter-torque: False
bullet-default-PD: False
max-path-num: 20
critic-layer-size: [256, 256]
train-step-num: 1
prioritized-exp-replay: True
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-layer-size: [256, 256]
epoch-num: 500
HLC-frequency: 25
state-dim: 25
action-dim: 12
squash-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-test-time: 10
loss-output-bound-coeff: 0.0
render-eval: False
epoch-step-num: 5000000
loss-entropy-coeff: 0.0
actor-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
gating-mask: [[1.0, 1.0]]
goal-weight: 0.4
imitation-weight: 0.4
LLC-frequency: 500
reward-scale: 0.1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gamma: 0.986
joint-interpolation: True
tau: 0.001
n-step: 1
env-id: HumanoidBalanceFilter-v0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
dsr-gait-freq: 1.667
critic-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-output-diff-coeff: 0
loss-output-smooth-coeff: 2.0
gating-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
actor-l2-reg: 0.0003
replay-start-size: 10000
record-start-size: 10000.0
task-weight: 0.2
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
