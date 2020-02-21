replay-start-size: 10000
max-episode-num: 5000000
epoch-step-num: 5000000
loss-output-smooth-coeff: 2.0
filter-action: True
actor-weight-decay: 1e-06
loss-output-diff-coeff: 0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
imitation-weight: 0.4
squash-action: True
max-test-time: 10
goal-weight: 0.4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-path-step: 5000
gating-layer-size: [128, 128]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
interpolation: False
max-train-time: 10
task-weight: 0.2
critic-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-buffer-size: 1000000
env-id: HumanoidBalanceFilter-v0
batch-size: 128
dsr-gait-period: 0.6
total-step-num: 2500000000
actor-lr: 0.0003
dsr-gait-freq: 1.667
critic-lr: 0.0003
epoch-num: 500
reward-scale: 0.1
replay-ratio: 1
HLC-frequency: 25
prioritized-exp-replay: True
action-dim: 12
rollout-step-num: 1
filter-torque: False
max-path-num: 20
render-eval: False
max-step-num: 2500000000
critic-l2-reg: 0.0003
gamma: 0.986
actor-activation-fn: ['relu', 'relu', 'None']
critic-activation-fn: ['relu', 'relu', 'None']
n-step: 1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
train-step-num: 1
expert-num: 2
actor-l2-reg: 0.0003
joint-interpolation: True
gating-mask: [[1.0, 1.0]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-entropy-coeff: 0.0
Physics-frequency: 1000
state-dim: 25
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
loss-output-bound-coeff: 0.0
tau: 0.001
record-start-size: 10000.0
critic-weight-decay: 1e-06
actor-layer-size: [256, 256]
