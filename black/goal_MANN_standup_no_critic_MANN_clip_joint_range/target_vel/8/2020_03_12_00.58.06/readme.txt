max-episode-num: 5000000
dsr-gait-freq: 1.667
actor-layer-size: [256, 256]
action-dim: 12
dsr-gait-period: 0.6
loss-output-bound-coeff: 0.0
replay-buffer-size: 1000000
loss-output-diff-coeff: 0
LLC-frequency: 500
loss-output-smooth-coeff: 2.0
total-step-num: 2500000000
batch-size: 128
replay-start-size: 10000
record-start-size: 10000.0
task-weight: 0.2
filter-action: True
expert-num: 8
critic-lr: 0.0003
Physics-frequency: 1000
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
train-step-num: 1
critic-l2-reg: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
max-train-time: 10
max-step-num: 2500000000
test-num: 4
filter-torque: False
prioritized-exp-replay: True
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
squash-action: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
gamma: 0.986
state-dim: 25
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
env-id: HumanoidBalanceFilter-v0
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
max-path-num: 20
loss-entropy-coeff: 0.0
max-test-time: 10
replay-ratio: 1
n-step: 1
actor-weight-decay: 1e-06
epoch-step-num: 5000000
max-path-step: 5000
reward-scale: 0.1
interpolation: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
rollout-step-num: 1
render-eval: False
epoch-num: 500
goal-weight: 0.4
critic-weight-decay: 1e-06
critic-activation-fn: ['relu', 'relu', 'None']
gating-activation-fn: ['relu', 'relu', 'None']
critic-layer-size: [256, 256]
joint-interpolation: True
actor-lr: 0.0003
HLC-frequency: 25
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
imitation-weight: 0.4
tau: 0.001
gating-layer-size: [128, 128]
