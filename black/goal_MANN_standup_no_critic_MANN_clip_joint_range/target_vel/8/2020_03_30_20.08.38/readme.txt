squash-action: True
env-id: HumanoidBalanceFilter-v0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
render-eval: False
replay-buffer-size: 1000000
critic-l2-reg: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-test-time: 10
max-episode-num: 5000000
rollout-step-num: 1
task-weight: 0.2
state-dim: 25
bullet-default-PD: False
actor-weight-decay: 1e-06
n-step: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-activation-fn: ['relu', 'relu', 'None']
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
max-path-num: 20
max-path-step: 5000
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
critic-layer-size: [256, 256]
actor-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
gamma: 0.986
loss-entropy-coeff: 0.0
actor-layer-size: [256, 256]
actor-lr: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
actor-l2-reg: 0.0003
epoch-step-num: 5000000
interpolation: False
loss-output-diff-coeff: 0
tau: 0.001
loss-output-bound-coeff: 0.0
replay-ratio: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-train-time: 10
dsr-gait-period: 0.6
expert-num: 8
prioritized-exp-replay: True
goal-weight: 0.4
loss-output-smooth-coeff: 2.0
action-dim: 12
epoch-num: 500
joint-interpolation: True
dsr-gait-freq: 1.667
LLC-frequency: 500
gating-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
gating-layer-size: [128, 128]
critic-weight-decay: 1e-06
imitation-weight: 0.4
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
max-step-num: 2500000000
HLC-frequency: 25
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
Physics-frequency: 1000
reward-scale: 0.1
filter-action: True
test-num: 4
total-step-num: 2500000000
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
record-start-size: 10000.0
replay-start-size: 10000
train-step-num: 1
