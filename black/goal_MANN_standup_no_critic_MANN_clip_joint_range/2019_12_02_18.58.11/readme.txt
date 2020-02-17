state-dim: 25
joint-interpolation: True
dsr-gait-period: 0.6
max-step-num: 2500000000
critic-weight-decay: 1e-06
squash-action: True
loss-output-diff-coeff: 0
bullet-default-PD: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
total-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
Physics-frequency: 1000
epoch-step-num: 5000000
actor-l2-reg: 0.0003
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
loss-output-bound-coeff: 0.0
critic-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 0.3
critic-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
actor-weight-decay: 1e-06
batch-size: 128
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-path-num: 20
n-step: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
max-path-step: 5000
LLC-frequency: 500
loss-output-smooth-coeff: 2.0
rollout-step-num: 1
loss-entropy-coeff: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
goal-weight: 0.4
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
HLC-frequency: 25
record-start-size: 10000.0
gamma: 0.986
gating-layer-size: [128, 128]
expert-num: 8
filter-action: True
action-dim: 12
actor-lr: 0.0003
actor-layer-size: [256, 256]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
max-episode-num: 5000000
render-eval: False
dsr-gait-freq: 1.667
interpolation: False
tau: 0.001
actor-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
max-train-time: 10
replay-ratio: 1
filter-torque: False
prioritized-exp-replay: True
replay-start-size: 10000
max-test-time: 10
reward-scale: 0.1
task-weight: 0.3
epoch-num: 500
