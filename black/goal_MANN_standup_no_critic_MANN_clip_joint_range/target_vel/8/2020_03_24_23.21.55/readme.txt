critic-l2-reg: 0.0003
filter-action: True
max-test-time: 10
replay-ratio: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
goal-weight: 0.4
dsr-gait-period: 0.6
max-path-num: 20
state-dim: 25
max-episode-num: 5000000
reward-scale: 0.1
max-train-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
n-step: 1
render-eval: False
total-step-num: 2500000000
filter-torque: False
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
critic-layer-size: [256, 256]
task-weight: 0.2
squash-action: True
actor-l2-reg: 0.0003
max-path-step: 5000
replay-buffer-size: 1000000
epoch-num: 500
env-id: HumanoidBalanceFilter-v0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-freq: 1.667
replay-start-size: 10000
test-num: 4
rollout-step-num: 1
action-dim: 12
record-start-size: 10000.0
loss-output-smooth-coeff: 2.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-layer-size: [128, 128]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
interpolation: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
epoch-step-num: 5000000
train-step-num: 1
bullet-default-PD: False
expert-num: 8
loss-output-diff-coeff: 0
loss-entropy-coeff: 0.0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-weight-decay: 1e-06
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
loss-output-bound-coeff: 0.0
joint-interpolation: True
actor-layer-size: [256, 256]
HLC-frequency: 25
Physics-frequency: 1000
actor-activation-fn: ['relu', 'relu', 'None']
prioritized-exp-replay: True
max-step-num: 2500000000
imitation-weight: 0.4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-lr: 0.0003
critic-lr: 0.0003
LLC-frequency: 500
critic-weight-decay: 1e-06
batch-size: 128
tau: 0.001
gamma: 0.986
critic-activation-fn: ['relu', 'relu', 'None']
