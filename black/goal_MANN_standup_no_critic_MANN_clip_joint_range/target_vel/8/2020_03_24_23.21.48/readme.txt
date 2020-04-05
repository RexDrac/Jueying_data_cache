actor-layer-size: [256, 256]
expert-num: 8
actor-l2-reg: 0.0003
prioritized-exp-replay: True
env-id: HumanoidBalanceFilter-v0
max-test-time: 10
n-step: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
task-weight: 0.2
loss-entropy-coeff: 0.0
goal-weight: 0.4
filter-action: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
joint-interpolation: True
max-step-num: 2500000000
loss-output-bound-coeff: 0.0
replay-start-size: 10000
gamma: 0.986
state-dim: 25
epoch-step-num: 5000000
critic-layer-size: [256, 256]
max-path-step: 5000
interpolation: False
max-episode-num: 5000000
batch-size: 128
total-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
squash-action: True
actor-weight-decay: 1e-06
Physics-frequency: 1000
HLC-frequency: 25
loss-output-diff-coeff: 0
render-eval: False
gating-layer-size: [128, 128]
loss-output-smooth-coeff: 2.0
reward-scale: 0.1
critic-lr: 0.0003
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
bullet-default-PD: False
action-dim: 12
actor-lr: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
LLC-frequency: 500
filter-torque: False
critic-weight-decay: 1e-06
tau: 0.001
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-num: 500
replay-buffer-size: 1000000
rollout-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
dsr-gait-period: 0.6
critic-l2-reg: 0.0003
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
imitation-weight: 0.4
replay-ratio: 1
gating-activation-fn: ['relu', 'relu', 'None']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-freq: 1.667
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
critic-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
record-start-size: 10000.0
test-num: 4
