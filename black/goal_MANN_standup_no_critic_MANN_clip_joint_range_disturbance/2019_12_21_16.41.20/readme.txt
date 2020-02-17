critic-weight-decay: 1e-06
state-dim: 25
max-train-time: 10
interpolation: False
filter-action: True
HLC-frequency: 25
max-test-time: 10
loss-output-bound-coeff: 0.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-step-num: 2500000000
actor-lr: 0.0003
max-episode-num: 5000000
loss-output-diff-coeff: 0
train-step-num: 1
gating-layer-size: [128, 128]
replay-ratio: 1
actor-activation-fn: ['relu', 'relu', 'None']
max-path-step: 5000
squash-action: True
gating-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
reward-scale: 0.1
imitation-weight: 0.4
critic-lr: 0.0003
actor-weight-decay: 1e-06
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-torque: False
loss-output-smooth-coeff: 2.0
total-step-num: 2500000000
dsr-gait-freq: 1.667
render-eval: False
Physics-frequency: 1000
action-dim: 12
rollout-step-num: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
env-id: HumanoidBalanceFilter-v0
critic-layer-size: [256, 256]
batch-size: 128
epoch-num: 500
prioritized-exp-replay: True
loss-entropy-coeff: 0.0
joint-interpolation: True
goal-weight: 0.4
bullet-default-PD: False
replay-buffer-size: 1000000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
record-start-size: 10000.0
actor-l2-reg: 0.0003
LLC-frequency: 500
tau: 0.001
replay-start-size: 10000
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
dsr-gait-period: 0.6
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-step-num: 5000000
task-weight: 0.2
max-path-num: 20
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
test-num: 4
expert-num: 8
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
critic-activation-fn: ['relu', 'relu', 'None']
gamma: 0.986
