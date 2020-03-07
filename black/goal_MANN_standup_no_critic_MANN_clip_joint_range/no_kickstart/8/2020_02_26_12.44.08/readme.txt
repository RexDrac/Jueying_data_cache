loss-output-diff-coeff: 0
gating-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
action-dim: 12
loss-entropy-coeff: 0.0
total-step-num: 2500000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-path-num: 20
gamma: 0.986
gating-layer-size: [128, 128]
n-step: 1
loss-output-smooth-coeff: 2.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
rollout-step-num: 1
test-num: 4
replay-start-size: 10000
max-episode-num: 5000000
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
bullet-default-PD: False
goal-weight: 0.4
squash-action: True
train-step-num: 1
critic-weight-decay: 1e-06
record-start-size: 10000.0
task-weight: 0.2
reward-scale: 0.1
env-id: HumanoidBalanceFilter-v0
epoch-step-num: 5000000
actor-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
dsr-gait-freq: 1.667
tau: 0.001
HLC-frequency: 25
critic-l2-reg: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
expert-num: 8
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
render-eval: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-ratio: 1
epoch-num: 500
dsr-gait-period: 0.6
LLC-frequency: 500
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 25
max-test-time: 10
max-train-time: 10
max-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
replay-buffer-size: 1000000
joint-interpolation: True
critic-activation-fn: ['relu', 'relu', 'None']
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
Physics-frequency: 1000
critic-lr: 0.0003
critic-layer-size: [256, 256]
filter-torque: False
filter-action: True
imitation-weight: 0.4
actor-layer-size: [256, 256]
loss-output-bound-coeff: 0.0
batch-size: 128
actor-weight-decay: 1e-06
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
interpolation: False
