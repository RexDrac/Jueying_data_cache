render-eval: False
goal-weight: 0.6
max-path-step: 5000
actor-weight-decay: 1e-06
gamma: 0.986
max-test-time: 10
state-dim: 25
gating-activation-fn: ['relu', 'relu', 'None']
n-step: 1
replay-buffer-size: 1000000
epoch-num: 500
loss-entropy-coeff: 0.0
total-step-num: 2500000000
actor-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
filter-action: True
reward-scale: 0.1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
batch-size: 128
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
critic-weight-decay: 1e-06
actor-layer-size: [256, 256]
expert-num: 8
max-train-time: 10
max-step-num: 2500000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
tau: 0.001
test-num: 4
record-start-size: 10000.0
replay-ratio: 1
bullet-default-PD: False
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
critic-lr: 0.0003
max-path-num: 20
joint-interpolation: True
dsr-gait-period: 0.6
critic-layer-size: [256, 256]
loss-output-smooth-coeff: 2.0
gating-layer-size: [128, 128]
task-weight: 0.2
imitation-weight: 0.2
Physics-frequency: 1000
action-dim: 12
prioritized-exp-replay: True
max-episode-num: 5000000
env-id: HumanoidBalanceFilter-v0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
squash-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-step-num: 5000000
train-step-num: 1
replay-start-size: 10000
loss-output-diff-coeff: 0
dsr-gait-freq: 1.667
actor-l2-reg: 0.0003
rollout-step-num: 1
loss-output-bound-coeff: 0.0
filter-torque: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
LLC-frequency: 500
