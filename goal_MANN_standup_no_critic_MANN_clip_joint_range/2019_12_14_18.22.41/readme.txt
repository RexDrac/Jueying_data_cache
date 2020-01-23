epoch-step-num: 5000000
gating-layer-size: [128, 128]
max-step-num: 2500000000
critic-layer-size: [256, 256]
dsr-gait-freq: 1.667
state-dim: 25
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-episode-num: 5000000
actor-weight-decay: 1e-06
max-path-step: 5000
env-id: HumanoidBalanceFilter-v0
max-test-time: 10
train-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
replay-ratio: 1
critic-l2-reg: 0.0003
loss-entropy-coeff: 0.0
goal-weight: 0.4
task-weight: 0.2
replay-start-size: 10000
loss-output-smooth-coeff: 2.0
joint-interpolation: True
max-path-num: 20
critic-lr: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
imitation-weight: 0.4
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-buffer-size: 1000000
reward-scale: 0.1
epoch-num: 500
loss-output-bound-coeff: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-lr: 0.0003
LLC-frequency: 500
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
critic-weight-decay: 1e-06
max-train-time: 10
test-num: 4
loss-output-diff-coeff: 0
total-step-num: 2500000000
tau: 0.001
Physics-frequency: 1000
actor-l2-reg: 0.0003
filter-torque: False
n-step: 1
prioritized-exp-replay: True
batch-size: 128
action-dim: 12
squash-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
gating-activation-fn: ['relu', 'relu', 'None']
render-eval: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
dsr-gait-period: 0.6
record-start-size: 10000.0
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-activation-fn: ['relu', 'relu', 'None']
expert-num: 8
rollout-step-num: 1
filter-action: True
gamma: 0.986
actor-layer-size: [256, 256]
