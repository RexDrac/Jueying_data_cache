replay-ratio: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-buffer-size: 1000000
Physics-frequency: 1000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
tau: 0.001
interpolation: False
dsr-gait-freq: 1.667
record-start-size: 10000.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
imitation-weight: 0.2
actor-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
rollout-step-num: 1
env-id: HumanoidBalanceFilter-v0
critic-layer-size: [256, 256]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
loss-entropy-coeff: 0.0
max-step-num: 2500000000
expert-num: 8
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
task-weight: 0.2
actor-l2-reg: 0.0003
train-step-num: 1
LLC-frequency: 500
actor-layer-size: [256, 256]
max-test-time: 10
prioritized-exp-replay: True
gamma: 0.986
max-train-time: 10
actor-weight-decay: 1e-06
render-eval: False
filter-action: True
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
batch-size: 128
test-num: 4
goal-weight: 0.6
state-dim: 25
n-step: 1
critic-l2-reg: 0.0003
joint-interpolation: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-bound-coeff: 0.0
filter-torque: False
total-step-num: 2500000000
replay-start-size: 10000
squash-action: True
gating-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [128, 128]
HLC-frequency: 25
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
dsr-gait-period: 0.6
actor-lr: 0.0003
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
epoch-step-num: 5000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
epoch-num: 500
max-path-num: 20
bullet-default-PD: False
loss-output-diff-coeff: 0
max-path-step: 5000
max-episode-num: 5000000
reward-scale: 0.1
