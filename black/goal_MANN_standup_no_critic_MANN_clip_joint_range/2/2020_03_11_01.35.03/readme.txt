squash-action: True
test-num: 4
max-train-time: 10
batch-size: 128
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
loss-output-smooth-coeff: 2.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
dsr-gait-freq: 1.667
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-episode-num: 5000000
interpolation: False
Physics-frequency: 1000
critic-lr: 0.0003
tau: 0.001
loss-entropy-coeff: 0.0
reward-scale: 0.1
filter-torque: False
HLC-frequency: 25
max-path-num: 20
dsr-gait-period: 0.6
gating-layer-size: [128, 128]
gamma: 0.986
prioritized-exp-replay: True
action-dim: 12
loss-output-diff-coeff: 0
critic-layer-size: [256, 256]
bullet-default-PD: False
critic-l2-reg: 0.0003
LLC-frequency: 500
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-layer-size: [256, 256]
actor-lr: 0.0003
record-start-size: 10000.0
n-step: 1
task-weight: 0.2
state-dim: 25
render-eval: False
gating-mask: [[1.0, 1.0]]
epoch-step-num: 5000000
loss-output-bound-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
replay-buffer-size: 1000000
max-test-time: 10
critic-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
expert-num: 2
replay-start-size: 10000
actor-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
train-step-num: 1
actor-weight-decay: 1e-06
imitation-weight: 0.4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
goal-weight: 0.4
joint-interpolation: True
actor-l2-reg: 0.0003
max-step-num: 2500000000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-step: 5000
epoch-num: 500
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-ratio: 1
env-id: HumanoidBalanceFilter-v0
rollout-step-num: 1
