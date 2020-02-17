critic-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
imitation-weight: 0.5
actor-lr: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [128, 128]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
env-id: HumanoidBalanceFilter-v0
replay-ratio: 1
loss-output-diff-coeff: 0
n-step: 1
max-test-time: 10
critic-lr: 0.0003
critic-weight-decay: 1e-06
train-step-num: 1
tau: 0.001
reward-scale: 0.1
loss-output-bound-coeff: 0.0
joint-interpolation: True
expert-num: 8
max-step-num: 2500000000
epoch-step-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
batch-size: 128
actor-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-layer-size: [256, 256]
squash-action: True
actor-l2-reg: 0.0003
filter-action: True
max-path-step: 5000
max-episode-num: 5000000
loss-output-smooth-coeff: 3.0
dsr-gait-period: 0.6
replay-start-size: 10000
max-train-time: 10
action-dim: 12
prioritized-exp-replay: True
Physics-frequency: 1000
state-dim: 25
gamma: 0.986
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
interpolation: False
record-start-size: 10000.0
max-path-num: 20
bullet-default-PD: False
rollout-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
epoch-num: 500
actor-weight-decay: 1e-06
actor-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
task-weight: 0.5
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
dsr-gait-freq: 1.667
render-eval: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
total-step-num: 2500000000
replay-buffer-size: 1000000
loss-entropy-coeff: 0.0
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
filter-torque: False
