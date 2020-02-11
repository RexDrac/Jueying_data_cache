action-bounds: [[-0.39  -2.79   0.66  -0.39  -2.79   0.66  -0.39  -1.884  0.66  -0.39
  -1.884  0.66 ]
 [ 0.39   0.348  2.73   0.39   0.348  2.73   0.39   0.348  2.73   0.39
   0.348  2.73 ]]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
dsr-gait-period: 0.6
action-dim: 12
render-eval: False
actor-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
max-test-time: 10
loss-output-bound-coeff: 0.0
task-weight: 0.2
loss-output-diff-coeff: 0
loss-entropy-coeff: 0.0
bullet-default-PD: False
gamma: 0.986
joint-interpolation: True
env-id: HumanoidBalanceFilter-v0
max-path-step: 5000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-weight-decay: 1e-06
max-path-num: 20
filter-action: True
batch-size: 128
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
gating-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
gating-layer-size: [128, 128]
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
dsr-gait-freq: 1.667
epoch-num: 500
imitation-weight: 0.4
max-step-num: 2500000000
critic-l2-reg: 0.0003
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
prioritized-exp-replay: True
actor-l2-reg: 0.0003
test-num: 4
HLC-frequency: 25
actor-layer-size: [256, 256]
state-dim: 25
replay-buffer-size: 1000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
filter-torque: False
replay-start-size: 10000
tau: 0.001
replay-ratio: 1
squash-action: True
rollout-step-num: 1
epoch-step-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-smooth-coeff: 2.0
critic-lr: 0.0003
actor-lr: 0.0003
train-step-num: 1
reward-scale: 0.1
n-step: 1
max-train-time: 10
critic-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
total-step-num: 2500000000
interpolation: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-num: 8
goal-weight: 0.4
max-episode-num: 5000000
