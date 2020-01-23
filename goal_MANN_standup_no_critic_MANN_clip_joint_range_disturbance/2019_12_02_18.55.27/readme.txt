max-step-num: 2500000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
action-dim: 12
max-episode-num: 5000000
critic-lr: 0.0003
epoch-step-num: 5000000
state-dim: 25
Physics-frequency: 1000
batch-size: 128
prioritized-exp-replay: True
rollout-step-num: 1
replay-ratio: 1
critic-layer-size: [256, 256]
replay-buffer-size: 1000000
joint-interpolation: True
n-step: 1
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
imitation-weight: 0.3
filter-torque: False
loss-output-smooth-coeff: 2.0
max-test-time: 10
actor-weight-decay: 1e-06
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
tau: 0.001
loss-entropy-coeff: 0.0
actor-l2-reg: 0.0003
gating-layer-size: [128, 128]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
critic-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
replay-start-size: 10000
max-path-num: 20
total-step-num: 2500000000
LLC-frequency: 500
loss-output-bound-coeff: 0.0
goal-weight: 0.4
loss-output-diff-coeff: 0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 8
gating-activation-fn: ['relu', 'relu', 'None']
render-eval: False
reward-scale: 0.1
train-step-num: 1
filter-action: True
max-path-step: 5000
critic-weight-decay: 1e-06
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
env-id: HumanoidBalanceFilter-v0
actor-lr: 0.0003
dsr-gait-freq: 1.667
squash-action: True
HLC-frequency: 25
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
test-num: 4
max-train-time: 10
dsr-gait-period: 0.6
interpolation: False
gamma: 0.986
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-layer-size: [256, 256]
task-weight: 0.3
