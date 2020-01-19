goal-weight: 0.4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-train-time: 10
replay-ratio: 1
record-start-size: 10000.0
actor-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
env-id: HumanoidBalanceFilter-v0
rollout-step-num: 1
train-step-num: 1
batch-size: 128
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-layer-size: [256, 256]
imitation-weight: 0.3
filter-torque: False
replay-buffer-size: 1000000
dsr-gait-freq: 1.667
bullet-default-PD: False
prioritized-exp-replay: True
n-step: 1
loss-output-smooth-coeff: 2.0
epoch-num: 500
LLC-frequency: 500
max-test-time: 10
critic-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.3
gating-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
joint-interpolation: True
dsr-gait-period: 0.6
max-episode-num: 5000000
test-num: 4
interpolation: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
squash-action: True
actor-weight-decay: 1e-06
state-dim: 25
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-layer-size: [128, 128]
actor-lr: 0.0003
gamma: 0.986
max-path-num: 20
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-l2-reg: 0.0003
max-step-num: 2500000000
actor-layer-size: [256, 256]
render-eval: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-bound-coeff: 0.0
action-dim: 12
tau: 0.001
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
actor-l2-reg: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
expert-num: 8
critic-activation-fn: ['relu', 'relu', 'None']
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-lr: 0.0003
Physics-frequency: 1000
loss-output-diff-coeff: 0
replay-start-size: 10000
epoch-step-num: 5000000
reward-scale: 0.1
filter-action: True
loss-entropy-coeff: 0.0
