gating-layer-size: [128, 128]
max-train-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
render-eval: False
env-id: HumanoidBalanceFilter-v0
prioritized-exp-replay: True
critic-l2-reg: 0.0003
train-step-num: 1
replay-start-size: 10000
actor-layer-size: [256, 256]
filter-action: True
actor-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
HLC-frequency: 25
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-num: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
replay-ratio: 1
max-test-time: 10
loss-output-bound-coeff: 0.0
task-weight: 0.2
max-path-step: 5000
loss-output-diff-coeff: 0
gating-activation-fn: ['relu', 'relu', 'None']
gamma: 0.986
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
total-step-num: 2500000000
loss-entropy-coeff: 0.0
goal-weight: 0.4
joint-interpolation: True
imitation-weight: 0.4
filter-torque: False
replay-buffer-size: 1000000
actor-l2-reg: 0.0003
loss-output-smooth-coeff: 2.0
tau: 0.001
reward-scale: 0.1
state-dim: 25
max-step-num: 2500000000
expert-num: 8
actor-lr: 0.0003
actor-weight-decay: 1e-06
n-step: 1
action-dim: 12
critic-activation-fn: ['relu', 'relu', 'None']
test-num: 4
critic-layer-size: [256, 256]
epoch-step-num: 5000000
Physics-frequency: 1000
record-start-size: 10000.0
interpolation: False
squash-action: True
critic-weight-decay: 1e-06
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
dsr-gait-freq: 1.667
max-episode-num: 5000000
bullet-default-PD: False
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
rollout-step-num: 1
max-path-num: 20
dsr-gait-period: 0.6
