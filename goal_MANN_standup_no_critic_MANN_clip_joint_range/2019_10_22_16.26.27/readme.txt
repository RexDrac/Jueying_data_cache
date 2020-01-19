actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-start-size: 10000
max-episode-num: 5000000
train-step-num: 1
epoch-num: 500
env-id: HumanoidBalanceFilter-v0
total-step-num: 2500000000
max-path-num: 20
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
expert-num: 8
tau: 0.001
state-dim: 25
filter-torque: False
critic-weight-decay: 1e-06
filter-action: True
Physics-frequency: 1000
batch-size: 128
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-entropy-coeff: 0.0
test-num: 4
reward-scale: 0.1
task-weight: 0.5
critic-l2-reg: 0.0003
replay-buffer-size: 1000000
squash-action: True
epoch-step-num: 5000000
record-start-size: 10000.0
critic-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
render-eval: False
actor-lr: 0.0003
actor-weight-decay: 1e-06
dsr-gait-freq: 1.667
critic-layer-size: [256, 256]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
joint-interpolation: True
imitation-weight: 0.5
actor-layer-size: [256, 256]
max-path-step: 5000
critic-lr: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
gamma: 0.986
max-train-time: 10
max-step-num: 2500000000
interpolation: False
n-step: 1
loss-output-diff-coeff: 0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
LLC-frequency: 500
actor-l2-reg: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
prioritized-exp-replay: True
max-test-time: 10
action-dim: 12
dsr-gait-period: 0.6
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
replay-ratio: 1
loss-output-smooth-coeff: 1.0
gating-layer-size: [128, 128]
loss-output-bound-coeff: 0.0
bullet-default-PD: False
rollout-step-num: 1
