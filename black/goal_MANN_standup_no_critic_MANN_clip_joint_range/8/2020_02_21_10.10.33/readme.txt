critic-lr: 0.0003
gating-layer-size: [128, 128]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-weight-decay: 1e-06
prioritized-exp-replay: True
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
action-dim: 12
total-step-num: 2500000000
critic-activation-fn: ['relu', 'relu', 'None']
test-num: 4
critic-l2-reg: 0.0003
loss-entropy-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
max-path-step: 5000
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
loss-output-bound-coeff: 0.0
replay-ratio: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-num: 8
state-dim: 25
interpolation: False
imitation-weight: 0.4
max-train-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-layer-size: [256, 256]
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
HLC-frequency: 25
loss-output-diff-coeff: 0
dsr-gait-freq: 1.667
replay-buffer-size: 1000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
train-step-num: 1
goal-weight: 0.4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
n-step: 1
replay-start-size: 10000
epoch-step-num: 5000000
env-id: HumanoidBalanceFilter-v0
bullet-default-PD: False
loss-output-smooth-coeff: 2.0
dsr-gait-period: 0.6
max-test-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
record-start-size: 10000.0
critic-layer-size: [256, 256]
reward-scale: 0.1
task-weight: 0.2
epoch-num: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-weight-decay: 1e-06
tau: 0.001
actor-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
max-episode-num: 5000000
actor-l2-reg: 0.0003
batch-size: 128
filter-action: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
max-step-num: 2500000000
gamma: 0.986
Physics-frequency: 1000
joint-interpolation: True
squash-action: True
filter-torque: False
render-eval: False
