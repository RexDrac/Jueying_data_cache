max-episode-num: 5000000
critic-layer-size: [256, 256]
max-path-num: 20
actor-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
critic-l2-reg: 0.0003
epoch-step-num: 5000000
render-eval: False
prioritized-exp-replay: True
test-num: 4
gamma: 0.986
state-dim: 25
n-step: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-num: 500
max-train-time: 10
interpolation: False
filter-torque: False
bullet-default-PD: False
critic-weight-decay: 1e-06
max-test-time: 10
replay-start-size: 10000
gating-activation-fn: ['relu', 'relu', 'None']
expert-num: 8
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-weight-decay: 1e-06
actor-layer-size: [256, 256]
replay-buffer-size: 1000000
record-start-size: 10000.0
critic-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
max-path-step: 5000
rollout-step-num: 1
goal-weight: 0.4
action-dim: 12
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
joint-interpolation: True
dsr-gait-freq: 1.667
dsr-gait-period: 0.6
squash-action: True
env-id: HumanoidBalanceFilter-v0
filter-action: True
tau: 0.001
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
imitation-weight: 0.4
gating-layer-size: [128, 128]
replay-ratio: 1
Physics-frequency: 1000
critic-lr: 0.0003
loss-entropy-coeff: 0.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
LLC-frequency: 500
batch-size: 128
loss-output-smooth-coeff: 2.0
reward-scale: 0.1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
train-step-num: 1
loss-output-diff-coeff: 0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-l2-reg: 0.0003
task-weight: 0.2
max-step-num: 2500000000
loss-output-bound-coeff: 0.0
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
