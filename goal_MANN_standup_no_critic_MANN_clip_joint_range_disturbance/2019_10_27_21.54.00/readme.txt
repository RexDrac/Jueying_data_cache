max-step-num: 2500000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
reward-scale: 0.1
squash-action: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
HLC-frequency: 25
max-path-step: 5000
replay-start-size: 10000
epoch-step-num: 5000000
replay-buffer-size: 1000000
prioritized-exp-replay: True
env-id: HumanoidBalanceFilter-v0
render-eval: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
test-num: 4
tau: 0.001
task-weight: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
n-step: 1
gamma: 0.986
batch-size: 128
replay-ratio: 1
actor-l2-reg: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
total-step-num: 2500000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-weight-decay: 1e-06
action-dim: 12
bullet-default-PD: False
LLC-frequency: 500
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
record-start-size: 10000.0
critic-lr: 0.0003
actor-lr: 0.0003
imitation-weight: 0.5
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
Physics-frequency: 1000
goal-weight: 0.5
actor-layer-size: [256, 256]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
dsr-gait-period: 0.6
epoch-num: 500
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
train-step-num: 1
loss-output-bound-coeff: 0.0
joint-interpolation: True
actor-activation-fn: ['relu', 'relu', 'None']
critic-layer-size: [256, 256]
loss-entropy-coeff: 0.0
interpolation: False
max-test-time: 10
expert-num: 8
loss-output-smooth-coeff: 1.0
max-train-time: 10
critic-l2-reg: 0.0003
filter-action: True
gating-layer-size: [128, 128]
gating-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
filter-torque: False
max-episode-num: 5000000
dsr-gait-freq: 1.667
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 25
max-path-num: 20
rollout-step-num: 1
loss-output-diff-coeff: 0
