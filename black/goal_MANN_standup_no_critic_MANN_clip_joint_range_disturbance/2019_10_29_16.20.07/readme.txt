filter-torque: False
dsr-gait-period: 0.6
Physics-frequency: 1000
task-weight: 0.3
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
total-step-num: 2500000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-weight-decay: 1e-06
expert-num: 8
n-step: 1
max-episode-num: 5000000
record-start-size: 10000.0
action-dim: 12
critic-l2-reg: 0.0003
loss-output-smooth-coeff: 2.0
prioritized-exp-replay: True
actor-lr: 0.0003
rollout-step-num: 1
critic-lr: 0.0003
imitation-weight: 0.3
reward-scale: 0.1
loss-entropy-coeff: 0.0
max-train-time: 10
test-num: 4
replay-start-size: 10000
bullet-default-PD: False
critic-layer-size: [256, 256]
HLC-frequency: 25
max-path-step: 5000
critic-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
gamma: 0.986
actor-l2-reg: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
squash-action: True
max-path-num: 20
env-id: HumanoidBalanceFilter-v0
render-eval: False
joint-interpolation: True
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
dsr-gait-freq: 1.667
epoch-num: 500
loss-output-diff-coeff: 0
actor-weight-decay: 1e-06
actor-layer-size: [256, 256]
max-test-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
max-step-num: 2500000000
batch-size: 128
gating-layer-size: [128, 128]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
goal-weight: 0.4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-ratio: 1
tau: 0.001
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
interpolation: False
loss-output-bound-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
train-step-num: 1
state-dim: 25
