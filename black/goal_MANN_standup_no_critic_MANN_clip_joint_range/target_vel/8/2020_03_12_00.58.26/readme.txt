actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
record-start-size: 10000.0
gating-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
critic-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
max-path-step: 5000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
gating-layer-size: [128, 128]
tau: 0.001
max-episode-num: 5000000
expert-num: 8
bullet-default-PD: False
critic-weight-decay: 1e-06
imitation-weight: 0.4
gamma: 0.986
rollout-step-num: 1
loss-output-diff-coeff: 0
prioritized-exp-replay: True
action-dim: 12
max-train-time: 10
filter-torque: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
squash-action: True
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
replay-start-size: 10000
actor-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-lr: 0.0003
filter-action: True
env-id: HumanoidBalanceFilter-v0
state-dim: 25
test-num: 4
max-step-num: 2500000000
task-weight: 0.2
dsr-gait-freq: 1.667
critic-lr: 0.0003
LLC-frequency: 500
loss-output-smooth-coeff: 2.0
actor-l2-reg: 0.0003
HLC-frequency: 25
batch-size: 128
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-entropy-coeff: 0.0
train-step-num: 1
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
critic-layer-size: [256, 256]
actor-weight-decay: 1e-06
epoch-num: 500
actor-layer-size: [256, 256]
render-eval: False
reward-scale: 0.1
goal-weight: 0.4
joint-interpolation: True
max-test-time: 10
replay-ratio: 1
epoch-step-num: 5000000
total-step-num: 2500000000
interpolation: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
dsr-gait-period: 0.6
loss-output-bound-coeff: 0.0
Physics-frequency: 1000
n-step: 1
