max-test-time: 10
interpolation: False
replay-buffer-size: 1000000
loss-output-diff-coeff: 0
LLC-frequency: 500
loss-output-smooth-coeff: 1.0
max-train-time: 10
critic-lr: 0.0003
total-step-num: 2500000000
max-path-step: 5000
replay-start-size: 10000
critic-layer-size: [256, 256]
n-step: 1
reward-scale: 0.1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
env-id: HumanoidBalanceFilter-v0
dsr-gait-period: 0.6
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
action-dim: 12
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
max-path-num: 20
squash-action: True
rollout-step-num: 1
render-eval: False
actor-weight-decay: 1e-06
epoch-num: 500
tau: 0.001
dsr-gait-freq: 1.667
max-step-num: 2500000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
joint-interpolation: True
epoch-step-num: 5000000
imitation-weight: 0.5
critic-l2-reg: 0.0003
train-step-num: 1
max-episode-num: 5000000
prioritized-exp-replay: True
actor-layer-size: [256, 256]
record-start-size: 10000.0
Physics-frequency: 1000
task-weight: 0.5
actor-l2-reg: 0.0003
test-num: 4
loss-entropy-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
critic-weight-decay: 1e-06
expert-num: 8
HLC-frequency: 25
actor-lr: 0.0003
gating-layer-size: [128, 128]
gamma: 0.986
state-dim: 25
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-ratio: 1
filter-torque: False
bullet-default-PD: False
filter-action: True
