imitation-weight: 0.5
loss-output-bound-coeff: 0.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
state-dim: 25
filter-action: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
rollout-step-num: 1
dsr-gait-freq: 1.667
dsr-gait-period: 0.6
task-weight: 0.5
actor-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
critic-l2-reg: 0.0003
n-step: 1
expert-num: 8
interpolation: False
replay-buffer-size: 1000000
reward-scale: 0.1
tau: 0.001
prioritized-exp-replay: True
loss-output-diff-coeff: 0
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-episode-num: 5000000
epoch-step-num: 5000000
max-train-time: 10
action-dim: 12
epoch-num: 500
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
HLC-frequency: 25
max-test-time: 10
filter-torque: False
gating-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [128, 128]
critic-weight-decay: 1e-06
actor-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
total-step-num: 2500000000
max-path-num: 20
train-step-num: 1
actor-lr: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-step-num: 2500000000
critic-lr: 0.0003
render-eval: False
replay-start-size: 10000
Physics-frequency: 1000
actor-weight-decay: 1e-06
bullet-default-PD: False
replay-ratio: 1
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
gamma: 0.986
LLC-frequency: 500
joint-interpolation: True
squash-action: True
loss-entropy-coeff: 0.0
test-num: 4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
batch-size: 128
