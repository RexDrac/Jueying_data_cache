gating-activation-fn: ['relu', 'relu', 'None']
test-num: 4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
loss-output-diff-coeff: 0
max-step-num: 2500000000
record-start-size: 10000.0
replay-buffer-size: 1000000
critic-layer-size: [256, 256]
render-eval: False
max-path-num: 20
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
critic-weight-decay: 1e-06
filter-action: True
gating-layer-size: [128, 128]
imitation-weight: 0.4
dsr-gait-freq: 1.667
reward-scale: 0.1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
batch-size: 128
joint-interpolation: True
critic-activation-fn: ['relu', 'relu', 'None']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
bullet-default-PD: False
actor-weight-decay: 1e-06
HLC-frequency: 25
prioritized-exp-replay: True
max-episode-num: 5000000
actor-lr: 0.0003
loss-output-bound-coeff: 0.0
dsr-gait-period: 0.6
train-step-num: 1
critic-lr: 0.0003
max-path-step: 5000
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
interpolation: False
squash-action: True
max-test-time: 10
actor-layer-size: [256, 256]
filter-torque: False
replay-start-size: 10000
epoch-num: 500
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
epoch-step-num: 5000000
loss-output-smooth-coeff: 2.0
state-dim: 25
goal-weight: 0.4
LLC-frequency: 500
gamma: 0.986
tau: 0.001
loss-entropy-coeff: 0.0
n-step: 1
task-weight: 0.2
rollout-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
env-id: HumanoidBalanceFilter-v0
actor-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
max-train-time: 10
replay-ratio: 1
total-step-num: 2500000000
expert-num: 8
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-l2-reg: 0.0003
