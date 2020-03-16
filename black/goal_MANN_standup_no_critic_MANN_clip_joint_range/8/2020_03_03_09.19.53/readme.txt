tau: 0.001
max-step-num: 2500000000
LLC-frequency: 500
gating-layer-size: [128, 128]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
replay-start-size: 10000
prioritized-exp-replay: True
bullet-default-PD: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
goal-weight: 0.4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
squash-action: True
epoch-step-num: 5000000
max-path-step: 5000
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
actor-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-layer-size: [256, 256]
loss-entropy-coeff: 0.0
task-weight: 0.2
rollout-step-num: 1
HLC-frequency: 25
test-num: 4
state-dim: 25
reward-scale: 0.1
dsr-gait-period: 0.6
loss-output-diff-coeff: 0
max-episode-num: 5000000
loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
expert-num: 8
actor-lr: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
train-step-num: 1
replay-buffer-size: 1000000
dsr-gait-freq: 1.667
actor-activation-fn: ['relu', 'relu', 'None']
gamma: 0.986
action-dim: 12
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
n-step: 1
replay-ratio: 1
actor-layer-size: [256, 256]
batch-size: 128
loss-output-smooth-coeff: 2.0
critic-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
interpolation: False
env-id: HumanoidBalanceFilter-v0
filter-torque: False
render-eval: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
max-test-time: 10
max-path-num: 20
total-step-num: 2500000000
epoch-num: 500
imitation-weight: 0.4
record-start-size: 10000.0
actor-weight-decay: 1e-06
filter-action: True
max-train-time: 10
Physics-frequency: 1000
