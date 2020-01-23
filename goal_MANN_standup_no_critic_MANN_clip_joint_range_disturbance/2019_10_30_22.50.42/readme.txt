actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
critic-layer-size: [256, 256]
tau: 0.001
actor-layer-size: [256, 256]
action-dim: 12
critic-activation-fn: ['relu', 'relu', 'None']
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-output-diff-coeff: 0
squash-action: True
state-dim: 25
n-step: 1
critic-weight-decay: 1e-06
dsr-gait-period: 0.6
critic-l2-reg: 0.0003
max-step-num: 2500000000
actor-weight-decay: 1e-06
Physics-frequency: 1000
max-episode-num: 5000000
max-path-num: 20
gating-layer-size: [128, 128]
max-path-step: 5000
filter-torque: False
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
reward-scale: 0.1
loss-output-smooth-coeff: 2.0
gating-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
HLC-frequency: 25
interpolation: False
goal-weight: 0.5
total-step-num: 2500000000
joint-interpolation: True
actor-lr: 0.0003
loss-output-bound-coeff: 0.0
actor-l2-reg: 0.0003
train-step-num: 1
test-num: 4
max-test-time: 10
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
env-id: HumanoidBalanceFilter-v0
gamma: 0.986
bullet-default-PD: False
actor-activation-fn: ['relu', 'relu', 'None']
dsr-gait-freq: 1.667
max-train-time: 10
LLC-frequency: 500
loss-entropy-coeff: 0.0
rollout-step-num: 1
prioritized-exp-replay: True
imitation-weight: 0.5
replay-buffer-size: 1000000
task-weight: 0.0
expert-num: 8
render-eval: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
replay-start-size: 10000
filter-action: True
record-start-size: 10000.0
epoch-step-num: 5000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
