max-path-step: 5000
render-eval: False
critic-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
record-start-size: 10000.0
goal-weight: 0.4
interpolation: False
gating-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
filter-action: True
replay-ratio: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
imitation-weight: 0.4
task-weight: 0.2
critic-l2-reg: 0.0003
train-step-num: 1
reward-scale: 0.1
epoch-step-num: 5000000
max-test-time: 10
filter-torque: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
loss-output-smooth-coeff: 2.0
gamma: 0.986
squash-action: True
batch-size: 128
state-dim: 25
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-activation-fn: ['relu', 'relu', 'None']
tau: 0.001
total-step-num: 2500000000
dsr-gait-period: 0.6
max-step-num: 2500000000
bullet-default-PD: False
replay-start-size: 10000
expert-num: 8
Physics-frequency: 1000
loss-output-bound-coeff: 0.0
critic-lr: 0.0003
max-path-num: 20
actor-lr: 0.0003
max-episode-num: 5000000
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
LLC-frequency: 500
prioritized-exp-replay: True
dsr-gait-freq: 1.667
joint-interpolation: True
rollout-step-num: 1
HLC-frequency: 25
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
env-id: HumanoidBalanceFilter-v0
critic-layer-size: [256, 256]
replay-buffer-size: 1000000
epoch-num: 500
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-diff-coeff: 0
gating-layer-size: [128, 128]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-weight-decay: 1e-06
action-dim: 12
test-num: 4
actor-layer-size: [256, 256]
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
critic-weight-decay: 1e-06
max-train-time: 10
n-step: 1
