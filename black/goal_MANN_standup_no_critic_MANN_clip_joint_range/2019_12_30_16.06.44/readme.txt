Physics-frequency: 1000
critic-l2-reg: 0.0003
replay-buffer-size: 1000000
epoch-num: 500
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
train-step-num: 1
max-step-num: 2500000000
actor-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.2
action-dim: 12
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-ratio: 1
loss-entropy-coeff: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-layer-size: [128, 128]
epoch-step-num: 5000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
n-step: 1
dsr-gait-freq: 1.667
render-eval: False
max-path-step: 5000
joint-interpolation: True
max-test-time: 10
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
prioritized-exp-replay: True
actor-lr: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
goal-weight: 0.4
imitation-weight: 0.4
test-num: 4
dsr-gait-period: 0.6
batch-size: 128
loss-output-smooth-coeff: 2.0
actor-layer-size: [256, 256]
bullet-default-PD: False
max-train-time: 10
reward-scale: 0.1
filter-torque: False
critic-layer-size: [256, 256]
HLC-frequency: 25
loss-output-bound-coeff: 0.0
max-episode-num: 5000000
rollout-step-num: 1
loss-output-diff-coeff: 0
replay-start-size: 10000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 8
LLC-frequency: 500
state-dim: 25
gating-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
actor-weight-decay: 1e-06
record-start-size: 10000.0
critic-weight-decay: 1e-06
actor-l2-reg: 0.0003
gamma: 0.986
squash-action: True
tau: 0.001
critic-lr: 0.0003
total-step-num: 2500000000
interpolation: False
critic-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
