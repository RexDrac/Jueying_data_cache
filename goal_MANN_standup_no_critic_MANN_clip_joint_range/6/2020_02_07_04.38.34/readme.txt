expert-num: 6
actor-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
tau: 0.001
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-bound-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
test-num: 4
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
gamma: 0.986
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
task-weight: 0.2
critic-l2-reg: 0.0003
actor-layer-size: [256, 256]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-weight-decay: 1e-06
train-step-num: 1
replay-start-size: 10000
critic-weight-decay: 1e-06
LLC-frequency: 500
critic-layer-size: [256, 256]
actor-l2-reg: 0.0003
max-path-step: 5000
filter-action: True
max-train-time: 10
interpolation: False
dsr-gait-period: 0.6
gating-layer-size: [128, 128]
HLC-frequency: 25
n-step: 1
Physics-frequency: 1000
loss-entropy-coeff: 0.0
loss-output-smooth-coeff: 2.0
epoch-step-num: 5000000
loss-output-diff-coeff: 0
filter-torque: False
total-step-num: 2500000000
bullet-default-PD: False
squash-action: True
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
render-eval: False
imitation-weight: 0.4
dsr-gait-freq: 1.667
max-step-num: 2500000000
goal-weight: 0.4
action-dim: 12
reward-scale: 0.1
max-path-num: 20
critic-lr: 0.0003
max-episode-num: 5000000
prioritized-exp-replay: True
replay-buffer-size: 1000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-test-time: 10
joint-interpolation: True
critic-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
gating-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
rollout-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
record-start-size: 10000.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
state-dim: 25
actor-lr: 0.0003
epoch-num: 500
